# 🎬 Análisis de comparación cinematográfica multiplataforma (1980-1989)

Este proyecto tiene como objetivo analizar el rendimiento crítico y comercial de 300 películas de la década de 1980, integrando datos de FilmAffinity e IMDb, junto con métricas financieras extraídas mediante scraping. 

## 📁 Estructura del repositorio

#### 📁 Source

- `paso01-descripcion_del_dataset.ipynb`  
  Exploración inicial del dataset: análisis de variables, completitud, estadísticas descriptivas y distribución por género y país.

- `paso02a-integracion_datos_financieros.ipynb`  
  Integración de datos financieros (presupuesto, recaudación, etc.) desde IMDb mediante técnicas de scraping.

- `paso02b-creacion_variables_calculadas.ipynb`  
  Generación de variables derivadas como ROI, éxito comercial, diferencia de puntuaciones y duración normalizada.

- `paso03-limpieza_de_los_datos.ipynb`  
  Imputación de valores perdidos, normalización de tipos de datos, y tratamiento de outliers.

- `paso04-analisis.ipynb`  
  Aplicación de modelos supervisados (Random Forest) y no supervisados (K-means), además de pruebas de hipótesis estadísticas.

- `peliculas_filmaffinity_1980-1989_imdb.csv`  
  Dataset original combinado desde FilmAffinity e IMDb.

#### 📁 Datasets

- `peliculas_filmaffinity_1980-1989_imdb.csv`  
  Dataset base con información combinada desde FilmAffinity e IMDb.

- `paso02a-peliculas_filmaffinity_1980-1989_imdb_integracion.csv`  
  Dataset enriquecido con variables financieras extraídas mediante scraping.

- `paso02b-peliculas_filmaffinity_1980-1989_imdb_derivadas.csv`
   Dataset con variables derivadas como ROI, éxito comercial, duración en minutos, etc.

- `paso03-peliculas_filmaffinity_1980-1989_limpio.csv`  
  Versión limpia y final del dataset, lista para análisis estadístico y modelado.

## 🎯 Objetivos

- Identificar factores que determinan el éxito comercial y crítico de una película.
- Comparar valoraciones entre FilmAffinity e IMDb.
- Clasificar películas en grupos mediante clustering.
- Explorar la rentabilidad por género cinematográfico.

## 📈 Tecnologías utilizadas

- Python 3.x
- Google Colab
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- BeautifulSoup4
