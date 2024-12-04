# Trabajo-Software
Vamos a hacer un trabajo de software y usaremos este repositorio para compartir los progresos, códigos y demás.

Todo el trabajo que se vaya haciendo cada uno por su cuenta y en grupo se tiene que subir a la carpeta correspondiente.
No se haceen los códigos en la propia presentación, eso se añade al final para evigtar lios.

Hay cuatro carpetas creadas, en la de data se guardan los datasets que necesitaremos.
En la carpeta de presentation se guardará la presemntación que hay que presentar el dia del examen final
En visualizations se guardan las gráficas que necesitaremos y presentaremos
Y, por último, en scripts se guardarán los códigos y funciones que se usarán.

Este es el objetivo:
El objetivo de la entrega es realizar un análisis de los datos electorales, llevando a cabo la depuración, los resúmenes y los gráficos que consideres necesarios, tanto de los resultados como de la precisión de las encuestas electorales.

En concreto, debes trabajar únicamente en el período de tiempo que incluye las elecciones desde 2008 hasta las últimas elecciones de 2019

Obligaciones:
Los datos deben ser convertidos a tidydata donde sea apropiado. (surveys hecho)

Debes incluir al menos un join entre tablas.

Recordatorio: información = varianza

Los paquetes {glue}, {forcats} y {lubridate} deben ser utilizados en algún punto

Los siguientes elementos deben usarse al menos una vez: mutate, summarise, group_by (o su equivalente), case_when

Deberéis definir al menos una función (con más de 5 líneas de código)

Contamos con muchos partidos que se presentan a las elecciones. Solo nos interesarán los siguientes partidos: (están todos ya filtrados en la tabla llamada "filtrado")

PARTIDO SOCIALISTA OBRERO ESPAÑOL (cuidado: tiene/tenía federaciones - sucursales - con otros nombres).

PARTIDO POPULAR

CIUDADANOS (cuidado: tiene/tenía federaciones - sucursales - con otros nombres).

PARTIDO NACIONALISTA VASCO

BLOQUE NACIONALISTA GALLEGO

CONVERGÈNCIA I UNIÓ

UNIDAS PODEMOS - IU (atención: aquí han tenido varios nombres - IU, Podem, Ezker Batua, ... - y no siempre se han presentado juntos, pero aquí los analizaremos como un conjunto).

ESQUERRA REPUBLICANA DE CATALUNYA

EH - BILDU (ahora son una coalición de partidos formada por Sortu, Eusko Alkartasuna, Aralar, Alternatiba).

MÁS PAÍS

VOX

Todo lo que no esté en alguno de los anteriores partidos debe ser correctamente reagrupado (y resumido) en OTROS (esto falta)

Las siglas deben ser usadas en las visualizaciones (ideas en https://r-graph-gallery.com/).

Debes usar todos los archivos en algún momento.

Debes descartar las encuestas que: (hecho)

-   se refieran a elecciones anteriores a 2008
-   sean a pie de urna
-   tamaño muestral desconocido o inferior a 500.
-   tenga 1 día o menos de trabajo de campo.

Deberás responder obligatoriamente a las siguientes preguntas (más aquellas que consideres analizar para distinguirte del resto)

¿Qué partido fue el ganador en los municipios con más de 100.000 habitantes (censo) en cada una de las elecciones?

¿Qué partido fue el segundo cuando el primero fue el PSOE? ¿Y cuando el primero fue el PP?

¿A quién beneficia la baja participación?

¿Cómo analizar la relación entre censo y voto? ¿Es cierto que determinados partidos ganan en las zonas rurales?

¿Cómo calibrar el error de las encuestas (recordemos que las encuestas son de intención de voto a nivel nacional)?

¿Qué casas encuestadoras acertaron más y cuáles se desviaron más de los resultados?

Debes incluir al menos 3 preguntas "originales" más que consideres interesantes de responder utilizando los datos.
