# Proyecto de Análisis de Ventas de Nike

Conversor CSV a SQLite:
# Conversor de CSV a SQLite

Este proyecto es una herramienta que convierte archivos CSV en una base de datos SQLite. Está diseñado para facilitar el almacenamiento y consulta de datos estructurados. Lee un archivo CSV que contiene información sobre ventas, selecciona columnas específicas y almacena los datos en una base de datos SQLite. Luego, realiza una consulta para verificar que los datos se han almacenado correctamente.

## Descripción

El script realiza las siguientes operaciones:
1. Lectura de datos: Lee un archivo CSV (`nike_sales_2024.csv`) que contiene datos de ventas de Nike.
2. Manejo de errores: Verifica si el archivo existe y si tiene un formato correcto.
3. Selección de columnas: Selecciona las columnas `Month`, `Region` y `Units_Sold` para su análisis.
4. Almacenamiento en SQLite: Almacena los datos seleccionados en una base de datos SQLite (`mi_base_de_datos.db`).
5. Verificación: Realiza una consulta a la base de datos para verificar que los datos se han almacenado correctamente.

## Datos

El dataset utilizado en este proyecto fue obtenido de Kaggle: Nike Global Sales Data (2024)([URL del dataset en Kaggle](https://www.kaggle.com/datasets/ayushcx/nike-global-sales-data-2024))
Agradezco a Kaggle por proporcionar el dataset utilizado en este proyecto.

## Instalación

1. Clona el repositorio: git clone https://github.com/macodevep/Conversor-CSV-a-SQLite.git
2. Instala los requisitos: `pip install -r requirements.txt`
