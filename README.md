# Martin's Thesis
## ¿Quién justifica qué? El rol del sentido de injusticia en las justificaciones de violencia en contexto de protesta

Link para avances aquí: https://thesis-justification-of-violence.github.io/thesis-report/index.html

Plantilla (template) para escritura y publicación de tesis/seminarios/memorias en FACSO UChile en formato pdf/html vía bookdown  (R)
[https://juancarloscastillo.github.io/tesisfacsodown/](https://juancarloscastillo.github.io/tesisfacsodown/)

# Preregistro

Para la elaboración de este pre-registro se ha seguido la plantilla de preinscripción de [AsPredicted.org](https://aspredicted.org/).

## **1) Recopilación de datos.** ¿Se han recopilado ya datos para este estudio?
Sí, se utilizan datos secundarios. Los datos corresponden al Estudio Longitudinal Social de Chile (ELSOC) efectuado por el Centro de Estudios de Conflicto y Cohesión Social (COES). El estudio es una encuesta panel con cuestionario estructurados, probabilística, estratificada, por conglomerados y multiétapicos. Los contenidos del cuestionario abordan distintos temas relacionados al conflicto y cohesión social en Chile. Actualmente, existen cuatro olas del estudio (2016 a 2019).

## **2) Hipótesis.** ¿Cuál es la pregunta principal o la hipótesis que se está probando en este estudio?

La pregunta principal de este proyecto de tesis es la siguiente:

> ¿Cuál es la relación entre el sentido de injusticia y las justificaciones de la violencia en contexto de protesta, tanto por el cambio social, como por el control social, en Chile al año 2019?

Las hipótesis del estudio son las siguientes:

- *H1a*: Individuos que evalúen mayor injusticia en la distribución de ingresos tenderán a justificar más la violencia por el cambio social.
- *H1b*: Individuos que evalúen mayor injusticia en la distribución de ingresos tenderán a justificar menos la violencia por el control social.
- *H2a*: Individuos pertenecientes a grupos desaventajados justifican más la violencia por el cambio social cuando evalúan  mayores niveles de injusticia en la distribución de ingresos
- *H2b*: Individuos pertenecientes a grupos desaventajados justifican menos la violencia por el control social cuando evalúan mayores niveles de injusticia en la distribución de ingresos

## **3) Variable dependiente.** Describa la(s) variable(s) clave(s) especificando cómo se medirán.

La variable principal de este estudio son las justificaciones de violencia en contexto de protesta. Esta variable se divide en dos tipos: por el cambio social y por el control social.

En el caso de la justificación de violencia por el cambio social, se utilizará un indicador:

- Que estudiantes tiren piedras a Carabineros en una marcha por la educación del país

En el caso de la justificación de la violencia por el control social, se usarán dos indicadores:

- Que Carabineros use la fuerza para reprimir una manifestación pacífica
- Que Carabineros desaloje a la fuerza a los estudiantes de un liceo en toma

Todas las variables consisten en indicadores tipo Likert de cinco categorías, siendo "Siempre se justifica" (5) la categoría más alta y "Nunca se justifica" (1) la categoría más baja.

## **4) Condiciones.** ¿Cuántas y qué condiciones se asignarán a los participantes?
El estudio es observacional, no experimental, por lo que no aplica.

## **5) Análisis.** Especifique exactamente qué análisis se realizará para examinar la pregunta / hipótesis principal

El análisis principal consistirá en regresiones logísticas ordinales, ibncluyendo un efecto de interacción para las hipótesis *H2a* y *H2b*.

## **6) Valores atípicos y exclusiones.** Describa exactamente cómo se definirán y tratarán los valores atípicos, y su(s) regla(s) precisa(s) para excluir las observaciones

Valores atípicos que denoten claramente errores de tipeo serán transformados a datos perdidos (e.g. un valor de 6 en una escala Likert que va de 1 a 5.).

La regla principal para excluir observaciones será la homogeneización de la base de datos. Esto significa la aplicación de método _listwise_ para eliminar casos perdidos en el conjunto de datos con las variables que serán utilizadas para el análisis. El objetivo de esto es trabajar con una base de datos que permita comparabilidad entre los análisis.

## **7) Tamaño de muestra.** ¿Cuántas observaciones se recopilarán o que determinará el tamaño de la muestra? No es necesario justificar la decisión, pero sea preciso sobre cómo se determinará exactamente el número.

La muestra total de la fuente de datos secundaria contiene 2135 casos. Como se señaló, el tamaño de muestra final para los análisis será producto de una homogeneización del conjunto de datos de las variables a utilizar en el análisis.

## **8) Otro.** ¿Algo más que le gustaría agregar? (por ejemplo, exclusiones de datos, variables recopiladas con fines exploratorios, análisis inusuales previstos)

Primero, el estudio usa datos secundarios. Dado este panorama, es necesario hacer la siguiente declaración: no se han realizado análisis multivariados ni pruebas de hipótesis a la fecha de este preregistro. Los únicos análisis que se han realizado son:

- Análisis descriptivos de la variable dependiente. Específicamente, se han analizado las frecuencias de cada indicador y las correlaciones entre los mismos. Cabe señalar que no se ha calculado la significancia estadística de las correlaciones. Este análisis descriptivo ha permitido plantear un plan de análisis más detallado.

- Análisis factoriales exploratorios. Se realizaron modelos exploratorios con uno, dos y tres factores. Así también, se probó un modelo confirmatorio tanto a dos como a tres factores. La realización de estos análisis permitió proponer un plan de análisis más detallado, así como también una sección exploratoria.

Todos los análisis aquí declarados pueden verse en el repositorio Github asociado a este preregistro.

Segundo, se incluirá un análisis exploratorio que consistirá en modelos de regresión lineal con los puntajes factoriales de un modelo de tres factores. Este modelo incluye un indicador que hasta ahora ha sido dejado fuera por definiciones teóricas, pero que podría ser empíricamente relevante para la discusión del objeto de estudio.

## **9) Nombre** Poner un título a este preregistro de AsPredicted

Justificaciones de violencia - Tesis de Pregrado en Sociología, UCH 2022

## Finalmente. A efectos de registro, indíquenos el tipo de estudio que está preinscribiendo.

Estudio observacional.
