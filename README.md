# TFG: Donacion de sangre
Proyecto final de grado de Business Analytics centrado en un análisis social sobre la donación de sangre en España entre los más jóvenes (concretamente, la conocida Generación Z)

Este repositorio contiene los notebooks, archivos de datos y resultados generados durante el análisis de conversaciones en redes sociales relacionadas con la donación de sangre.

El proyecto se centra en la recopilación, limpieza y análisis de publicaciones y comentarios procedentes de distintas plataformas, con el objetivo de estudiar percepciones, barreras, actitudes y patrones de discurso a partir de técnicas de análisis de texto.

## Estructura del repositorio

El repositorio está organizado en varias carpetas según la fase del trabajo y la procedencia de los datos.

### 1. Extracción de datos por plataforma

Se incluyen cuatro carpetas principales correspondientes a las plataformas analizadas:

- `Tiktok/`
- `Instagram/`
- `Twitter/`
- `Reddit scrapping/`

Cada una de estas carpetas contiene:

- El notebook utilizado para la extracción de datos
- Los archivos CSV generados a partir de dicha extracción

### 2. Limpieza y análisis

- `Limpieza + analisis/`

Esta carpeta reúne los notebooks y archivos intermedios relacionados con el procesamiento y análisis de los datos. Incluye, entre otros:

- Limpieza y preprocesamiento del texto
- Tokenización y normalización
- Eliminación de stopwords
- Lematización
- Análisis de n-gramas
- Análisis de sentimiento
- Modelado de tópicos

También contiene algunos archivos CSV generados durante las distintas etapas del flujo de trabajo.

### 3. Carpeta de gráficos

- `Graficos/`

En esta carpeta se almacenan las visualizaciones generadas a lo largo del análisis, incluyendo gráficos descriptivos, comparativas entre plataformas, resultados de sentimiento, distribuciones de tópicos y otras representaciones útiles para interpretar los datos.

## Metodología general

El desarrollo del proyecto sigue una secuencia estructurada de trabajo:

1. Extracción de datos desde distintas redes sociales
2. Limpieza y preprocesamiento del texto
3. Análisis exploratorio de frecuencias y patrones lingüísticos
4. Análisis de n-gramas
5. Modelado de tópicos
6. Análisis de sentimiento
7. Generación de gráficos y resultados finales

## Tecnologías utilizadas

Las principales herramientas utilizadas en este proyecto son:

- Python
- Jupyter Notebook
- Pandas
- NLTK
- spaCy
- Gensim
- Matplotlib
- Seaborn

## Observaciones

- Los datos utilizados proceden de fuentes públicas y han sido tratados con fines exclusivamente académicos.
- La estructura del repositorio refleja el flujo real de trabajo seguido durante el proyecto.
- Algunos archivos CSV corresponden a datos originales y otros a resultados intermedios generados durante el preprocesamiento y análisis.

## Autora

Susana Fraga
