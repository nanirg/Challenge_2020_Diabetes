# Challenge_2020_Diabetes

Parte 1 - Descripción de datos:

Dado el dataset, se espera que cada equipo lea el nombre de la variable y entienda la información que codifica. De esta información debe extraer los rangos en los que debe moverse cada variable y por lo tanto buscar si existen nulos. Ha de notarse que cuando se genera un dataset es frecuente que en ausencia de dato se introduzcan valores que no tienen sentido dada la información que representa la variable, los cuales deben buscar.

Además de realizar esta tarea, se espera que obtengan una descripción de la distribución de datos de cada variable, una información básica de media, moda, cuartiles, mínimo y máximo (en caso de variables no categóricas). Igualmente, se deberá estudiar la correlación entre variables del conjunto de datos, de cara a buscar si existe información repetida y explorar qué variables son candidatas a combinar en la siguiente fase.


Parte 2 - Alteraciones del conjunto de datos

Una vez entendido el conjunto de datos, el siguiente paso es editarlo y limpiarlo. En primer lugar se deben rellenar aquellos valores que se han detectado como nulos, con la política de reemplazo que considere cada grupo (media, moda, mediana, eliminar la fila etc). Una vez no queden nulos en el dataset, se debe proceder a buscar variables que se puedan añadir al conjunto de datos. Ya que solo se dispone de una fuente, estas variables (en caso de que se consideren relevantes) se obtendrán como combinación de las variables ya presentes en el dataset. De cara a la obtención de estas variables, se recomienda la representación de las mismas en distintos diagramas (barplot o scatterplot) para estudiar su distribución de manera visual y ver la posible existencia de patrones.


Parte 3 - Entrenamiento

Una vez editado el conjunto de datos a gusto y consideración del grupo, se procederá a buscar y entrenar un modelo que resuelva el ejercicio. Ya que cada modelo depende de uno o más hiperparámetros que han de ser configurados por cada grupo, se espera que se haga un estudio de los distintos valores que puede tomar y dar un motivo por el cual se está eligiendo un determinado valor. Una vez más, las representaciones gráficas resultan de gran ayuda en este apartado. 

Finalmente, se deben analizar los resultados del modelo, en clasificación por lo general se utiliza una matriz de confusión, para analizar qué casos son más conflictivos para el modelo y analizar si es un escenario conveniente o si por el contrario se debe buscar otra métrica para la selección del modelo.    
