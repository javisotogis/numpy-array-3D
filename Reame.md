# Proyecto: Gráfico de Array 3D en Python

## Descripción
Este proyecto genera un array tridimensional utilizando la biblioteca `numpy`, con valores aleatorios entre -100 y 100, y lo representa gráficamente en dos dimensiones usando `matplotlib`. La representación gráfica es una proyección del array 3D sumada a lo largo de uno de sus ejes (el eje Z). 

Una comparación breve:
- Un **array 3D de numpy** es una estructura de datos flexible que permite manejar datos multidimensionales de forma eficiente, comúnmente utilizada en análisis numérico.
- Un **raster monobanda**, en cambio, es un formato de datos geoespaciales que representa información en una cuadrícula bidimensional. Cada celda contiene un valor asociado, que puede ser comparable a una rebanada bidimensional de un array 3D.

La principal diferencia radica en el propósito: mientras un array de numpy es una herramienta de cálculo genérica, los rasters están diseñados específicamente para almacenar y analizar datos espaciales.

## Requisitos
Para ejecutar este código, necesitas tener instalado Python y las siguientes bibliotecas:

- `numpy`
- `matplotlib`

### Instalación de dependencias
Ejecuta el siguiente comando para instalar las dependencias necesarias:

```bash
pip install numpy matplotlib
```

## Uso
1. Descarga o copia el script `3d_array_plot.py` en tu máquina.
2. Ejecútalo desde la terminal o cualquier entorno de Python:

```bash
python 3d_array_plot.py
```

3. El gráfico generado mostrará una representación 2D del array 3D y será exportado como un archivo llamado `3d_array_projection.png`.

## Código
El script crea un loop y realiza las siguientes tareas:
1. Crea un array tridimensional con dimensiones predefinidas (`10x10x10`) y valores aleatorios entre -100 y 100.
2. Proyecta los valores del array 3D en una matriz bidimensional mediante la suma acumulativa a lo largo del eje Z.
3. Genera un gráfico usando la proyección 2D con `matplotlib`.
4. Exporta el gráfico a un archivo PNG.

## Archivos generados
- **3d_array_projection.png**: Archivo de imagen que contiene la representación gráfica del array proyectado.

## Contacto
Si tienes preguntas o sugerencias sobre este proyecto, no dudes en contactarme. ¡Espero que este proyecto sea útil y educativo!
