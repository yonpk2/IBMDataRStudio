Práctica Final Asignatura Herramientas del Científico de Datos - R

La práctica final de la asignatura consiste en resolver una serie de ejercicios de R. Se debe adjuntar el script en formato .rmd y html, debe ser íntegramente ejecutable.
Se recomienda comentar el código explicando que se ha hecho en cada apartado y porque se ha recurrido a dicha solución.
La práctica está formada por 14 apartados cuya puntuación es de un punto cada uno. La práctica forma el 100% de la nota total, la mitad del total corresponde al ejercicio de Python y la otra mitad para R.
El dataset es IBM.csv
El objetivo general, es realizar un análisis exploratorio de datos. Estos son los objetivos a realizar:
1.	Carga el dataset como dataframe (el valor 999 es nulo) y muestra sus primeras filas, su resúmen estadístico y la estructura de sus columnas.
2.	Reemplaza todos los valores nulos de la columna "Open", por su mediana
3.	Divide la columna "Date" en "Dia", "Mes" y "Año".
4.	Cambia la columna Año a factor.
5.	Devuelve el precio más alto de cada año.
6.	Muestra una tabla de frecuencias para cada año.
7.	Obtén una nueva columna que se llame "Diferencias" y que se el resultado de restar al precio más alto el precio más bajo.
8.	Ordena el dataset de forma ascendente por la columna "Diferencias".
9.	Muestra un resúmen estadístico del dataset en función de los siguientes valores por cada año:
a.	Precio más alto de apertura.
b.	Precio más bajo de cierre.
c.	Media de la columna "Diferencia".
d.	Número de elementos para cada año.
10.	Muestra el sumatorio de la variable Volumen para todos los años.
11.	Obtén dos histogramas para las variables de precio de apertura y cierre, rellena los histogramas en función del año.
12.	Muestra un diagrama de dispersión entre los precios más altos y más bajos, además muestra su recta de ajuste.
13.	Obtén un diagrama de caja y bigotes de la variable Adj.Close por año.
14.	Muestra para cada año un diagrama de densidad para la variable "Volume".
