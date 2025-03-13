# 📊 Análisis del clima con datos de AEMET | ✨ Generado con Quarto

Este repositorio contiene un informe generado con **Quarto** que analiza datos meteorológicos de la **AEMET (Agencia Estatal de Meteorología de España)**. 

## 📑 Descripción del Proyecto

El objetivo del informe es seleccionar y analizar un conjunto de datos meteorológicos que abarque más de un mes. Para ello, se utiliza la API de AEMET para extraer información relevante y generar visualizaciones que ayuden a entender las tendencias climáticas.

## 📂 Contenido del Repositorio

- **`Informe_AEMET.qmd`** → Archivo Quarto con el análisis y la generación del informe.
- **`README.md`** → Información sobre el proyecto y cómo utilizarlo.

## 🚀 Cómo Usarlo

1. **Descargar el archivo**  
   Puedes descargar el informe desde este enlace:  
   📥 [Descargar Informe_AEMET.qmd](https://raw.githubusercontent.com/marcoss6/AEMET-ClimateTrends/main/Informe_AEMET.qmd)

2. **Abrir y ejecutar en Quarto**  
   - Para generar el informe en HTML o PDF, necesitas tener **Quarto** instalado.  
   - Ejecuta en la terminal:  
     ```bash
     quarto render Informe_AEMET.qmd
     ```
   - Esto generará un informe en formato HTML.

3. **Reproducir el análisis**  
   - Asegúrate de obtener una **API Key de AEMET** y configurarla en el código para acceder a los datos.

## 📌 Notas

- La API Key utilizada en el código debe reemplazarse por una clave válida obtenida desde [AEMET Open Data](https://opendata.aemet.es/centrodedescargas/altaUsuario).
- Se recomienda utilizar un entorno de ejecución con soporte para Python para procesar los datos correctamente.


