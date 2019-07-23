# Listas con R

Una aproximación amable a las listas de R

##  Que son las listas

**R** cuenta con diferentes estructuras de datos:

* Vectores
* Data Frames
* **Listas**
* Matrices
* Arrays

La mayoría de las estructuras de datos tienen restricciones en el tipo de datos que pueden contener.
Es decir los vectores pueden formarse de números, pero no de **números y texto**. De intentarlo ambos se convertirían en 
texto. Con los **data.frames** se pueden tener distintos tipos de datos en cada **columna**, pero no diferentes tipos en
la misma columna. Matrices y arrays, que son arreglos con un mayor número de dimensiones, tienen limitaciones similares 
a la de los vectores.

Las listas por el contrario son arreglos de datos que pueden contener cualquier otro tipo de datos, desde vectores hasta
otras listas. Y de hecho esas listas internas pueden permitir la existencia de otras listas.

Al no tener estas restricciones, las listas se convierten en uno de las estructuras de datos mas versatiles que podemos 
explotar en **R**
