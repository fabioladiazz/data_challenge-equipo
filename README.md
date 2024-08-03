# Data Challenge 2024 - Equipo

## Descripción

Este repositorio contiene el trabajo realizado por el equipo "Equipo" para el Data Challenge 2024. A continuación se describen los archivos y el flujo de trabajo seguido para la visualización de datos.

## Video

En el drive se puede acceder al video que explica el proyecto por medio de Storytelling de los datos.

## Archivos

1. **adjudicaciones.csv** y **procedimientos.csv**: Estos archivos contienen los datos crudos utilizados para el análisis. Debido a su gran tamaño, no se pudieron subir directamente al repositorio. Para obtener estos archivos, por favor consultar la página https://sites.google.com/view/datachallengecostarica/datos-concurso?authuser=0.
   
2. **lineasproc.csv**: Este archivo contienen los datos crudos utilizados para el análisis más una columna calculada llamada total.

3. **data.ipynb**: Este notebook realiza el procesamiento de los datos contenidos en `adjudicaciones.csv`,`lineasproc.csv` y `procedimientos.csv`. El resultado de este procesamiento es el archivo `df_final.csv`, que ya se encuentra incluido en el repositorio.

4. **df_final.csv**: Este archivo es el resultado del procesamiento realizado en `data.ipynb`. Contiene los datos listos para ser utilizados en la generación de visualizaciones.

5. **gráficos.ipynb**: Este notebook toma `df_final.csv` como entrada y genera las visualizaciones que se utilizan en el video de presentación del proyecto.

## Flujo de Trabajo

1. **Procesamiento de Datos**: Ejecutar el notebook `data.ipynb` para procesar los datos crudos y generar `df_final.csv`.

2. **Generación de Visualizaciones**: Con `df_final.csv` generado en el paso anterior, ejecutar el notebook `gráficos.ipynb` para producir las visualizaciones.

## Instrucciones

1. Clonar este repositorio.
2. Obtener los archivos `adjudicaciones.csv` y `procedimientos.csv` de la página https://sites.google.com/view/datachallengecostarica/datos-concurso?authuser=0.
3. Colocar los archivos en el mismo directorio que los notebooks.
4. Ejecutar `data.ipynb` para generar `df_final.csv`.
5. Ejecutar `gráficos.ipynb` para generar las visualizaciones.

---

Equipo "Equipo"
Data Challenge 2024

