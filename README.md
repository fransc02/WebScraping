
# <h1 align=center> **Web Scraping - Yahoo Finance** </h1>

## Introducción
Este proyecto tiene como objetivo extraer, procesar y analizar datos financieros de diferentes acciones listadas en Yahoo Finance. Utilizando web scraping para analizar el HMTL de la pagina web para extraer y manipular los datos financieros.

## Objectivos del proyecto
+ **Obtener** datos financieros de empresas listadas en Yahoo Finance.
+ **Seleccionar y procesar** ciertos datos financieros para su análisis.
+ **Calcular ratios** financieros clave para evaluar el rendimiento de las empresas.
+ **Almacenar** los datos procesados en archivos CSV para su posterior análisis y visualización.

## Flujo de Trabajo

El flujo de trabajo se dividio en varias etapas:

1. ***Extracción de Información de Perfil de Acciones***: Se obtiene información de perfil, incluido el sector y la industria, de cada acción extraido de la web de Yahoo Finance.

2. ***Procesamiento de Precios de Acciones***: Se recopilan datos históricos de precios de acciones de cada acción y se procesan para su análisis posterior.

3. ***Procesamiento de Datos Financieros Seleccionados***: Se extraen los estados financieros clave, como el estado de resultados, el balance general y el flujo de efectivo, para cada acción. Luego, se seleccionan métricas financieras específicas y se calculan ratios financieros importantes para su análisis.

4. ***Almacenamiento de Datos***: Se almacenan los datos procesados en archivos CSV para su posterior análisis y visualización.

## Herramientas Utilizadas

**Python**: Lenguaje de programación utilizado para escribir el script.

Bibliotecas de Python:
+ requests: Para realizar solicitudes HTTP a Yahoo Finance.
+ BeautifulSoup: Para analizar HTML y extraer datos de la página web.
+ pandas: Para manipular y analizar datos en forma de DataFrames.
+ numpy: Para realizar cálculos numéricos.
+ yfinance: Para obtener datos históricos de precios de acciones.
+ datetime: Para trabajar con fechas.