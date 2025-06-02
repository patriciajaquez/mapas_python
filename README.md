# mapas_python

Visualización interactiva de datos geoespaciales de España y el mundo utilizando Python, GeoPandas y Folium.

## Descripción

Este proyecto permite explorar y visualizar mapas interactivos de países y provincias, con especial enfoque en España. Utiliza datos públicos de [Natural Earth](https://www.naturalearthdata.com/) y herramientas de Python para el análisis y visualización de datos geográficos.

## Características

- Visualización de países del mundo y sus atributos.
- Mapas coropléticos por población.
- Mapa interactivo de España y sus provincias.
- Herramientas interactivas: capas, minimapa, regla de medida, tooltips y clusters de marcadores.
- Uso de datos vectoriales (Shapefile) y procesamiento con GeoPandas.

## Estructura del proyecto
```
mapas_python/ 
│ ├── mapas/ # Datos geográficos (Natural Earth) 
│ ├── ne_110m_admin_0_countries_lakes.shp 
│ └── ne_10m_admin_1_states_provinces/ 
│     └── ne_10m_admin_1_states_provinces.shp 
├── mapas.ipynb # Notebook principal con el código de análisis y visualización 
├── mapa.html # Mapa mundial interactivo 
├── mapa_espana.html # Mapa interactivo de España 
├── mapa_poblacion.html # Mapa coroplético por población 
├── mapa_provincias_espana.html # Mapa interactivo de provincias de España 
└── README.md # Este archivo
```

## Instalación

1. Clona el repositorio:
    ```sh
    git clone https://github.com/patriciajaquez/mapas_python.git
    cd mapas_python
    ```

2. Instala las dependencias necesarias:
    ```sh
    pip install geopandas folium matplotlib cartopy shapely plotly
    ```

3. Descarga los datos de [Natural Earth](https://www.naturalearthdata.com/downloads/) y colócalos en la carpeta [mapas](http://_vscodecontentref_/7) si no están incluidos.

## Uso

Abre el notebook [mapas.ipynb](http://_vscodecontentref_/8) en Jupyter Notebook o Visual Studio Code y ejecuta las celdas para:

- Cargar y explorar datos geoespaciales.
- Visualizar mapas interactivos.
- Generar archivos HTML con los mapas para compartir o publicar.

También puedes abrir directamente los archivos HTML generados (`mapa.html`, [mapa_espana.html](http://_vscodecontentref_/9), etc.) en tu navegador.

## Créditos

- Datos geográficos: [Natural Earth](https://www.naturalearthdata.com/)
- Librerías: [GeoPandas](https://geopandas.org/), [Folium](https://python-visualization.github.io/folium/)
