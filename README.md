# Proyecto final energía sostenible

En este repositorio encontrarás un dataset proporcionado por Kaggle donde se encuentran diversos datos para medir las relaciones de los países con los tipos de electricidad (fósil, nuclear y renovables) en un periodo de 20 años (2000-2020). También existen diversos notebooks de Jupyter, uno donde se realizó un EDA y otro para realizar las predicciones de emisiones de Co2. Además, existe una carpeta donde el dataset proporcionado fue transformado a Base de Datos para lograr un modelo normalizado, así como otra carpeta donde se encuentra un archivo de PowerBI para realizar el análisis.

## Status

Ironhack Data Analytics Final Project. Beta version.

## Motivation

La motivación para realizar este proyecto fue poder explorar un poco más a nivel global hacía donde parece virar el sector eléctrico en el mundo, para así poder comprender el impacto que pueden tener las energías renovables para el futuro más cercano. Debido a los problemas acudiantes que tenemos actualmente con el calentamiento global, así como el deterioro de la capa de Ozono, veo más necesario que nunca comprobar si el mundo parece abrazar más las energías renovables que antes. Además, es interesante poder observar como ciertas políticas como la Agenda 2030 también puede afectar a estas tendencías de consumo de energías, por ejemplo, según un artículo de Naciones Unidas: " La Agencia Internacional de Energías Renovables (o IRENA, por sus siglas en inglés) calcula que el 90 % de la electricidad mundial puede, y debe, tener su origen en las energías renovables para el año 2050.". Todo parece indicar que nos inclinamos a un mundo donde el uso de las energías renovables será mayor.

## Technology stack

Este proyecto ha sido generado en Python para poder realizar tanto el EDA, la creación de la Base de Datos, así como las predicciones. 

Librerías utilizadas en Python:

 1. "Pandas" para obtener y devolver DataFrames.
 2. "SQLAlchemy" para poder obtener la base de datos y el modelo normalizado.
 3. "Matplotlib" y "Seaborn" para generar los gráficos.
 4. "Geopandas" para graficar los mapas.
 5. "Sklearn" para el preprocessing del modelo predicitivo.
 6. "Sarimax" para el modelo predictivo.

## Use and operation

Dentro de los dos notebooks, el primero tiene un EDA con algunos gráficos, así como la creación de los `.db` para poder crear un modelo relacional e introducirlo después en PowerBI. El segundo notebook contiene el código necesario para generar las predicciones, cuyo modelo utilizado fue Sarimax. Además, existe un archivo `.pbix` donde poder visualizar los gráficos generados PowerBI.

## Architecture

1. El dataset fue tratado y generado en `.db` para llevarlo a PowerBI.
2. También se generó una predicción a 5 años con Python, utilizando Sarimax.
3. Los datos fueron traslados a PowerBI para su visualización. 
 
## Resources

* Artículo [Naciones Unidas](https://www.un.org/es/climatechange/raising-ambition/renewable-energy).
* Dataset original de [Kaggle](https://www.kaggle.com/datasets/anshtanwar/global-data-on-sustainable-energy).
