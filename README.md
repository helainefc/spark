# spark
## Ejercicio 1. Quién es Quién en los Precios ![image](images/logo2018.jpg)

	
Descargar la Base de datos histórica de [Quién es Quién en los Precios](https://datos.gob.mx/busca/dataset/quien-es-quien-en-los-precios/resource/d89a59ae-a42a-4d71-8c38-dd21d02027ab "The best search engine for privacy")
de PROFECO y resolver las siguientes preguntas:
<strong>
<ol>
<li>¿Cuántos registros hay?</li>
<li>¿Cuántas categorías?</li>
<li>¿Cuántas cadenas comerciales están siendo monitoreadas (y, por lo tanto, reportadas
    en esa base de datos)?</li>
<li>¿Cuáles son los productos más monitoreados en cada estado de la república?</li>
<li>¿Cuál es la cadena comercial con mayor variedad de productos monitoreados?</li>
</ol></strong>

Para el procesamiento de los datos y el análisis exploratorio se utilizará Spark SQL.

## Ejercicio 2. Aeropuertos en el mundo.
El archivo demo.csv contiene una tabla con información de aeropuertos en el mundo. El ejercicio consite
en realizar las siguientes tareas:
<strong>
<ol>
<li>Generar un diccionario a partir de la columna country (country_id,country)</li>
<li>Escribir el diccionario como CSV desde spark</li>
<li>Leer el CSV generado y hacer inner join con demo.csv</li>
</ol></strong>

El dataframe, después del inner join, debe tener el mismo número de registros que el archivo
original. 