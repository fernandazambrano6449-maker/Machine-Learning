# Regresión Logística - Predicción de Supervivencia en el Titanic

Este proyecto lo hice para practicar regresión logística, un modelo que sirve para predecir si algo pertenece a una categoría (en este caso, si un pasajero sobrevivió o no).

## ¿Qué hice?

- Usé el dataset del Titanic ya limpio, con variables como clase, sexo, edad, tarifa y tamaño de familia
- Entrené un modelo de regresión logística para predecir si un pasajero sobrevivió
- Evalué el modelo con una matriz de confusión, además de métricas como precision y recall
- Grafiqué la curva ROC y calculé el AUC para ver qué tan bueno es el modelo distinguiendo entre sobrevivientes y no sobrevivientes
- Analicé qué variables tuvieron más peso en la predicción

## ¿Qué aprendí?

El modelo obtuvo un AUC de 0.88, lo que indica un buen desempeño distinguiendo entre quién sobrevivió y quién no. Las variables que más influyeron en la predicción fueron el sexo, la clase del pasajero, la tarifa pagada y la edad — lo cual tiene sentido con lo que se sabe históricamente del Titanic (mujeres, pasajeros de mejor clase y niños tuvieron más probabilidad de sobrevivir).

## Herramientas usadas

- Python
- pandas
- scikit-learn
- matplotlib
- seaborn
