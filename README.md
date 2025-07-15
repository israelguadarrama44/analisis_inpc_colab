# analisis_inpc_colab
Proyecto de análisis de datos con Google Colab: Tendencia y distribución del INPC mensual.
# Análisis Exploratorio del INPC Mensual en México

Este repositorio contiene un notebook de Google Colab (`analisis_inpc_mensual.ipynb`) para realizar un análisis exploratorio rápido del Índice Nacional de Precios al Consumidor (INPC) en México. Utiliza datos históricos para visualizar tendencias y distribuciones.

---

## Contenido del Proyecto

* **`analisis_inpc_mensual.ipynb`**: El notebook de Google Colab que contiene el código completo para:
    * Cargar el conjunto de datos CSV (`conjunto_de_datos_inpc_mensual.csv`).
    * Realizar una limpieza básica de datos (conversión de fechas, manejo de nulos).
    * Generar visualizaciones clave (tendencia del INPC, distribución).
* **`conjunto_de_datos_inpc_mensual.csv`**: El archivo de datos original utilizado para el análisis.

---

## ¿Qué preguntas responde este análisis?

Con este análisis exploratorio, podemos responder rápidamente preguntas como:

* **¿Cómo ha evolucionado el INPC a lo largo del tiempo?** (Tendencia general).
* **¿Cuál es el rango y la distribución de los valores del INPC?**
* **¿Existen diferentes categorías de INPC y cómo se comparan sus tendencias?** (Si aplica según los datos en la columna `CONCEPTO`).

---

## Cómo usar

1.  **Abrir en Google Colab:** Haz clic en el archivo `analisis_inpc_mensual.ipynb` en este repositorio. Una vez abierto en GitHub, busca el botón **"Open in Colab"** (Abrir en Colab) para ejecutarlo directamente.
2.  **Subir el CSV:** Asegúrate de que el archivo `conjunto_de_datos_inpc_mensual.csv` esté en tu entorno de Colab (puedes subirlo manualmente o montando Google Drive si ya está allí).
3.  **Ejecutar las celdas:** Ejecuta cada celda del notebook para ver el análisis paso a paso.

---

## Herramientas Utilizadas

* **Python**
* **Pandas** (para manipulación de datos)
* **Matplotlib** y **Seaborn** (para visualizaciones)
* **Google Colab** (entorno de desarrollo)

---

## Autor

Israel Guadarrama Rodriguez
