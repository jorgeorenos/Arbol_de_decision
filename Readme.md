# Modelos de clasificación

Con el conocido conjunto de datos del Titanic se estimó un modelo logístico y un árbol de decisión con el que se pretende predecir si un pasajero sobrevive al hundimiento del Titanic.

El modelo logístico mostró una precisión del 78% mientras que el árbol de decisión un 77%. Esto es algo que se puede apreciar en sus respectivas matrices de confusión.
|   |   |
|---|---|
|![Matriz de confusión logistica](https://github.com/jorgeorenos/Arbol_de_decision/blob/main/Imagenes/Matriz%20de%20confusi%C3%B3n%20modelo%20log%C3%ADstico.jpg)| ![Matriz de confusión arbol](https://github.com/jorgeorenos/Arbol_de_decision/blob/main/Imagenes/Matriz%20de%20confusi%C3%B3n%20%C3%A1rbol%20de%20decisi%C3%B3n.jpg)|

Esto es algo que también se evidencia en sus curvas ROC y que nos da la pauta para pensar de que el modelo logístico es el mejor para la clasificación. 

![Curva ROC](https://github.com/jorgeorenos/Arbol_de_decision/blob/main/Imagenes/ROC.jpg)

Aunque es factible pensar esto, también pudo deberse a la casualidad dada la muestra que se tomó, por lo que se procede a simular los modelos un total de 250 veces con distintas muestras para corroborar los resultados.

![Simulación](https://github.com/jorgeorenos/Arbol_de_decision/blob/main/Imagenes/ROC%20simulaci%C3%B3n.jpg)

Con lo anterior corroboramos que el modelo logístico es mejor para predicir si un pasajero del Titanic sobrevive o no al hundimiento.
