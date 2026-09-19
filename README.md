# Proyecto 6 — Análisis de una empresa de telecomunicaciones: ConnectaTel

## Objetivo del proyecto

Analizar el comportamiento de uso de los clientes de ConnectaTel en México y Colombia, identificando patrones de consumo de llamadas y mensajes, segmentos de clientes y comportamientos atípicos.

El objetivo es generar insights que permitan comprender mejor a los clientes y apoyar la optimización de los planes y la experiencia del usuario.

## Datasets utilizados

- `plans.csv`: información de los planes disponibles, precios, minutos, mensajes, GB incluidos y costos adicionales.
- `users_latam.csv`: información de los clientes, incluyendo edad, ciudad, fecha de registro, plan y fecha de cancelación.
- `usage.csv`: registros de llamadas y mensajes, incluyendo duración y cantidad de mensajes.

## Etapas del análisis

1. Exploración inicial de los datasets.
2. Identificación y tratamiento de valores faltantes e inconsistencias.
3. Conversión y validación de tipos de datos.
4. Integración de la información de usuarios y uso.
5. Análisis estadístico y descriptivo.
6. Identificación de valores atípicos mediante BoxPlot e IQR.
7. Segmentación de clientes por edad y nivel de uso.
8. Visualización de los principales patrones encontrados.
9. Elaboración de insights y recomendaciones para el negocio.

## Cómo ejecutar el notebook

El proyecto fue desarrollado en Python utilizando Jupyter Notebook y puede ejecutarse también en Google Colab.

Para reproducir el análisis:

1. Abrir el archivo `.ipynb` en Jupyter Notebook o Google Colab.
2. Cargar los datasets utilizados en el proyecto.
3. Ejecutar las celdas del notebook en orden.
4. Verificar que los archivos `plans.csv`, `users_latam.csv` y `usage.csv` estén disponibles en la ruta indicada en el notebook.

## Guía de reproducción

Para reproducir el análisis, se deben ejecutar las etapas en el siguiente orden:

1. Cargar las librerías y los datasets.
2. Explorar la estructura y calidad de los datos.
3. Tratar valores faltantes e inconsistencias.
4. Validar y transformar las fechas y variables necesarias.
5. Agregar el uso de llamadas y mensajes por cliente.
6. Integrar la información en `user_profile`.
7. Crear los segmentos `grupo_uso` y `grupo_edad`.
8. Generar las visualizaciones.
9. Analizar los outliers.
10. Revisar el insight ejecutivo y las recomendaciones.

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook
- Google Colab
