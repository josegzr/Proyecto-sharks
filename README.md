# Proyecto-sharks
1. miramos cual es el shape del dataframe para saber y tener una idea general de como es

2.hacemos una copia del dataframe original para poder editarlo y limpiarlo

3. vamos a ver cuantos nulos hay y si podemos borrar filas

4. limpieza de countries, areas y location

5 voy a limpiar la fila de country con un diccionario para que tengan nombres estandar

6 voy a copiar la fila de country en la fila de location y con un dicionario voy a poner los oceanos o mares donde estan

7 aqui veo cuantos ataques hay por oceano sin haber limpiado de nans la base 
Location
pacific ocean        4033
atlantic ocean        845
indian ocean          221
mediterranean sea     208
caribbean sea         201
chinese sea            38
red sea                10
norway sea              1
baltic sea              1

8 voy a crear una nueva columna con el pais y el oceano/mar en el que esta pasando y eliminar las dos ultimas columnas que son todo NAN


9 voy a intentar rellenar los nulos de sex y de name

10 voy a limpiar las columnas injury y Fatal(Y/N)

11 donde hay una Y en Fatal pongo en age no cumplira mas y asi me quito algun NAN de por medio

12 voy a limpiar todo de NAN y lo dejo terminado

13 cuento los unique values de location para conseguir los datos numericos de mi objetivo que en este caso es saber cuantos ataques ha habido por los oceanos mas grandes y algun mar

pacific ocean        73.353041
atlantic ocean       14.970439
caribbean sea         3.737331
indian ocean          3.695101
mediterranean sea     3.357264
chinese sea           0.675676
red sea               0.190034
norway sea            0.021115

14 Esto solo es para ver los datos del objetivo final borramos todos los datos que no son representativos porque tienen menos de un 30% de datos.
al final nos hemos quedado con un numero de 3474 filas y 23 columnas que es el 70% una vez limpiada la base de datos y que representa a los ataques que se han prodicido en el oceano pacifico.







