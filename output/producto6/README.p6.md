# Descripción
Set de 2 archivos, en formato CSV y JSON, que dan cuenta de la tasa de incidencia acumulada y de los casos confirmados acumulados en cada una de las comunas de Chile, según residencia, conforme a los informes epidemiológicos publicados por el Ministerio de Salud del país. 

Se entiende por caso confirmado la persona que cumple con los criterios de definición de caso sospechoso con una muestra positiva de SARS-CoV-2.

Se entiende por comuna de residencia la comuna que la persona declara como su vivienda habitual. 

Se entiende por casos acumulados el número total de casos confirmados desde el primer caso confirmado hasta la fecha de elaboración del reporte o informe. 

Se entiende por tasa de incidencia acumulada el número total de casos acumulados en relación a la población susceptible de enfermar en un período determinado. 

**Nota aclaratoria 1: El archivo no contempla los casos con región o comuna desconocida, es decir, aquellos casos en que no se registró la región de vivienda habitual en la notificación o bien son casos con domicilio en el extranjero. 

**Nota aclaratoria 2:  Los informes epidemiológicos del Ministerio de Salud informan del último día contabilizado para efectos de la elaboración de cada uno de ellos, habitualmente con corte a las 21 hrs. 

**Nota aclaratoria 3: Previo al 15 de abril de 2020 los informes epidemiológicos del Ministerio de Salud no entregaban datos de confirmados notificados en comunas con bajo número de casos, para proteger la identidad de las personas contagiadas. 

# Fuente
Informes epidemiológicos publicados periódicamente por el Ministerio de Salud de Chile. Ver en:
https://www.minsal.cl/nuevo-coronavirus-2019-ncov/informe-epidemiologico-covid-19/

A su vez, el Ministerio de Salud utiliza como fuente para la elaboración de estos informes el Sistema de notificación EPIVIGILA, del Departamento de Epidemiología, DIPLAS. 

# Frecuencia de actualización
Cada 2 a 3 días. 

# Columnas y valores
Los archivos contienen las columnas ‘Población’, ‘Casos Confirmados’, ‘Fecha’, ‘Código Región’’, ‘Nombre Región’, ‘Código Provincia’, ‘Provincia’, ‘Código Comuna 2017’ y ‘Tasa’’. Estos valores están separados entre sí por comas (csv). 
