#Introduccion.

Me presento soy Lucas Rodriguez, estudiante de la carrera de Data Science en SoyHenry actualmente em encuentro en la etapa de labs.

En este segundo Proyecto se nos solicito la creacion de un modelo de aprendizaje automatico para poder categorizar los precios de inmubles brindados en un dataset
llamado Train, que el mismo fue el que utilize para entrenar dicho algoritmo.
Tambien se nos brindo un dataset llamado test para que pongamos a prueba la eficiencia de nuestro modelo.
Lo que debiamos tener en cuenta para esta clasificacion era dicho precio de este inmueble, si el mismo era menor a USD 999 deberia ser clasificado como low o 1
y si el precio del inmuble era mayor a 999 deberia ser clasficado como high o 0.


#Eda.

Dado el problema, comenze con el profeso de limpieza(EDA) de los datos identificando las columnas con valores nulos y completandolos en los casos donde esas columnas eran
necesrias par el modelo, tambien se realizaron dummis en las columnas categoricas que mas influian en el aprendiaje del modelo.
Tambien fue necesaria la creacion de un Pipeline, para canalizar de una mejor manera el flujo de los datos hacia el modelo en este caso un Arbol de decicion

#Herramientas usadas / archivos utilizados

Visual estudio code
Python
Train.parquet
Test.parquet
