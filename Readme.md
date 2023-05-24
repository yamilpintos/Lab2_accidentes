**Contexto**
Los accidentes aéreos son eventos inesperados e indeseados que involucran aeronaves y se producen daños físicos a personas o a la propia aeronave. Un accidente aéreo puede involucrar cualquier tipo de aeronave, incluyendo aviones comerciales, aviones privados, helicópteros, planeadores y globos aerostáticos.

Los accidentes aéreos pueden ser causados por diversos factores, como errores humanos, fallos de equipos, problemas meteorológicos, problemas de mantenimiento, fallas en la gestión del tráfico aéreo, problemas de diseño o problemas de fabricación. Y en cuanto a sus consecuencias, pueden ser tanto en términos de pérdidas humanas como económicas.

Es por eso que la industria de la aviación, las autoridades reguladoras y los investigadores trabajan incansablemente para mejorar la seguridad de la aviación y prevenir futuros accidentes.

Por esto, el análisis de datos históricos de accidentes aéreos es fundamental para mejorar la seguridad de la aviación. La recopilación y el análisis sistemático de los datos de accidentes pueden ayudar a los investigadores a identificar patrones, tendencias y factores contribuyentes que podrían llevar a mejoras en la seguridad, desde ayudar a mejorar la capacitación de los pilotos y el personal de mantenimiento, así como a mejorar el diseño y la fabricación de aviones y equipos de aviación.


**Análisis Exploratorio de Datos de Accidentes de Aviones**

Este proyecto tiene como objetivo realizar un análisis exploratorio de datos de accidentes de aviones a lo largo del tiempo. Se utiliza un proceso de ETL (Extract, Transform, Load) para extraer, transformar y cargar los datos, seguido de un análisis exploratorio de datos (EDA) para obtener información y conocimientos relevantes.

**Proceso de ETL**

Extracción de datos: Los datos utilizados se obtuvieron de una fuente confiable, como una base de datos o un archivo en formato CSV. En este caso, los datos se encuentran en un archivo llamado "AccidentesAviones.csv".

Transformación de datos: Durante esta etapa, se realiza un procesamiento de los datos para prepararlos para su análisis. Esto puede incluir limpieza de datos, manejo de valores faltantes, eliminación de duplicados y conversión de tipos de datos. En este proyecto, se aplicó una transformación especial en la columna "summary" para extraer palabras relevantes que ayuden a entender los accidentes de aviones.

Carga de datos: Una vez que los datos están limpios y transformados, se cargan en una estructura de datos adecuada para su análisis. En este proyecto, se utilizó un DataFrame de la biblioteca Pandas de Python para almacenar y manipular los datos.

**Análisis Exploratorio de Datos (EDA)**
Una vez que los datos se han cargado correctamente, se realiza un análisis exploratorio para obtener información valiosa sobre los accidentes de aviones a lo largo del tiempo. A continuación, se detallan algunas de las técnicas utilizadas en el EDA:

Mapas de calor y correlación de Pearson: Se utilizan mapas de calor para visualizar la correlación entre diferentes variables relacionadas con los accidentes de aviones. Esto permite identificar posibles relaciones y dependencias entre los datos. La correlación de Pearson se calcula para determinar la fuerza y dirección de la relación entre las variables.

Gráficos para aclarar el tema: Se utilizan diferentes tipos de gráficos, como histogramas, diagramas de dispersión y gráficos de líneas, para visualizar y comprender mejor los datos. Estos gráficos ayudan a identificar patrones, tendencias y características destacadas relacionadas con los accidentes de aviones.

Análisis de outliers y anomalías: Se lleva a cabo un análisis detallado de outliers y anomalías en los datos. Esto implica identificar valores atípicos o inusuales que pueden afectar el análisis y las conclusiones. Se aplican técnicas estadísticas y visualizaciones específicas para identificar y comprender estos casos especiales.

Limpieza de datos para inferencias en Power BI: Se realiza una limpieza adicional de los datos para prepararlos para su uso en Power BI. Esto puede implicar la transformación de datos, el manejo de valores faltantes o la creación de nuevas variables.


**KPI´S**

**Tasa de Mortalidad por Accidente**:

Métrica: Porcentaje de personas fallecidas con respecto al número total de accidentes.
Cálculo: (Cantidad de fallecidos / Número total de accidentes) * 100.

**Tasa de Mortalidad por Accidentes por Falla**:

Métrica: Porcentaje de personas fallecidas en accidentes atribuidos a fallas técnicas o de mantenimiento.
Cálculo: (Cantidad de fallecidos en accidentes por falla / Número total de accidentes por falla) * 100.

**Tasa de Mortalidad por Accidentes por Clima**:

Métrica: Porcentaje de personas fallecidas en accidentes relacionados con condiciones climáticas adversas.
Cálculo: (Cantidad de fallecidos en accidentes por clima / Número total de accidentes por clima) * 100.

**Tasa de Mortalidad por Estrellarse**:

Métrica: Porcentaje de personas fallecidas en accidentes donde la causa principal fue el estrellamiento de la aeronave.
Cálculo: (Cantidad de fallecidos en accidentes por estrellamiento / Número total de accidentes por estrellamiento) * 100.

 **Accidentes por Aerolínea**:

Métrica: Número total de accidentes ocurridos por cada aerolínea.
Cálculo: Contar el número de accidentes para cada aerolínea en el conjunto de datos.

 **Accidentes por Tipo de Avión**:

Métrica: Número total de accidentes ocurridos para cada tipo de avión.
Cálculo: Contar el número de accidentes para cada tipo de avión en el conjunto de datos.