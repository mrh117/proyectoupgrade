## Lódica de negocio
La aplicación se basará en la siguiente estructura en cuanto a la lógica de negocio y procesamiento:
 - Procesado de los datos: obtendremos los datos a partir de páginas html que presentan una estructura similar
 - Generación del resultado: el cliente introducirá una serie de características sobre él mismo y sus objetivos, a partir de los cuales
   se generará una lista de titulaciones ordenadas según lo adecuadas que sean para él. Los parámetros que se tendrán en cuenta serán,
   entre otros:
    - Capacidades académicas del usuario comparadas con la dificultad de cada titulación
    - Requisitos mínimos del usuario sobre la empleabilidad y retribución económica de los empleos relacionados con el grado
    - Preferencias de carrera del usuario

## Obtención de los datos
Los datos los obtendremos a partir de portales de la universidad de Granada que nos los ofrecen tanto en forma de archivos ordenados como 
en páginas webs. Serán los siguientes:
 - [Estadísticas de satisfacción de los grados en archivos estructurados](https://opendata.ugr.es/dataset/rendimiento-academico-en-grados)
 - [Estadísticas de satisfacción de Ing. Informática en formato web](https://grados.ugr.es/informatica/static/CMSRemoteManagement/*/vic_cal/_dir_remotos/base_grado/_list_/indicadores)
 - [Observatorio de empleo](https://empleo.ugr.es/observatorio/consulta)
