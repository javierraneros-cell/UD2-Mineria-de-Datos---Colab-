# UD2-Mineria-de-Datos - Colab

En esta actividad se va a trabajar con conjunto de datos que contiene las marcas de los alumnos de un centro de alto rendimiento en diferentes pruebas atléticas. Concretamente, los campos que se recogen son los siguientes:

grupo clase a la que pertenece cada alumno (A o B)

-  100m lisos: marca en la prueba de 100 metros lisos
-  400m lisos: marca en la prueba de 400 metros lisos
-  100m vallas: marca en la prueba de 100 metros vallas
-  1500m lisos: marca en la prueba de 1500 metros lisos
-  salto horizontal: marca en el salto de longitud
-  lanzamiento de peso: marca en lanzamiento de peso o de bala (bola de acero)
-  salto de altura: marca en el salto vertical de altura
-  disco: marca en lanzamiento de disco
-  pértiga: marca en salto con pértiga
-  jabalina: marca en lanzamiento de jabalina

El objetivo final es calcular una única medida que permita determinar el rendimiento de cada alumno. Como se tratan de diferentes pruebas medidas en diferentes unidades, resulta complicado encontrar la forma de resumir los resultados en un único valor numérico. Para esta tarea se va a utilizar el análisis de componentes principales que permite reducir el número de dimensiones manteniendo la mayor cantidad de información posible. 

Concretamente, se desea reducir el número de dimensiones a 1.
