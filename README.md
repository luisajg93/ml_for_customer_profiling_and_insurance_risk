# ml_for_customer_profiling_and_insurance_risk
Proyecto de ML para análisis de clientes de seguros: similitud para marketing, predicción de siniestros (probabilidad y número), y enmascaramiento de datos para privacidad.
***Proyecto desarrollado como evaluación final del Sprint de Algebra lineal del Bootcamp de Data Scientist de TripleTen.***

## Contexto del proyecto
La compañía de seguros Sure Tomorrow quiere resolver varias tareas con la ayuda de machine learning y te pide que evalúes esa posibilidad.

- Tarea 1: encontrar clientes que sean similares a un cliente determinado. Esto ayudará a los agentes de la compañía con el marketing.
- Tarea 2: predecir la probabilidad de que un nuevo cliente reciba una prestación del seguro. ¿Puede un modelo de predictivo funcionar mejor que un modelo dummy?
- Tarea 3: predecir el número de prestaciones de seguro que un nuevo cliente pueda recibir utilizando un modelo de regresión lineal.
- Tarea 4: proteger los datos personales de los clientes sin afectar al modelo del ejercicio anterior. Es necesario desarrollar un algoritmo de transformación de datos que dificulte la recuperación de la información personal si los datos caen en manos equivocadas. Esto se denomina enmascaramiento u ofuscación de datos. Pero los datos deben protegerse de tal manera que no se vea afectada la calidad de los modelos de machine learning. No es necesario elegir el mejor modelo, basta con demostrar que el algoritmo funciona correctamente.

## Objetivo del proyecto
- Utilizar modelos de aprendizaje no supervisado para identificar clientes similares.
- Predicción de probabilidades de reclamación de seguros.
- Ofuscación de datos basada en algebra lineal. 

## Modelos de machine learning creados
- Linear Regression
- KNN

## Librerías principales utilizadas
- pandas
- matplotlib
- seaborn
- numpy
- sklearn
- imblearn

## Resultados
- En este proyecto se crea un modelo de identificación de clientes basado en aprendizaje no supervisado con vecinos más cercanos (KNN)
- Se puso a prueba el efecto del escalamiento en la identificación de clientes. 
- Se creó un modelo de regresión lineal desde cero basado en algebra lineal.
- Se demuestra analíticamente la viabilidad del ofuscamiento de datos basado en algebra lineal.
- Se prueba el ofuscamiento de datos en el modelo de regresion lineal creado. 
- En el archivo 'proyecto' se puede encontrar el desglose completo desde el EDA hasta la prueba de ofuscamiento. 