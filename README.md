# Predicción de atenciones IRAG mediante árboles de decisión

## Descripción del proyecto

Este proyecto consiste en el desarrollo de un modelo de inteligencia artificial para predecir la cantidad semanal de atenciones relacionadas con la Infección Respiratoria Aguda Grave (IRAG), utilizando datos históricos.

Se implementa el algoritmo de árbol de decisión de regresión (*Decision Tree Regressor*), con el propósito de identificar patrones en el comportamiento de las atenciones y estimar posibles valores futuros.

## Objetivo

Desarrollar un modelo predictivo que permita estimar las atenciones semanales por IRAG a partir de variables históricas y temporales.

## Tecnologías utilizadas

- Python
- Google Colab
- Pandas y NumPy
- Scikit-learn
- Matplotlib
- Streamlit
- Joblib

## Variables utilizadas

El modelo emplea las siguientes variables predictoras:

- Año.
- Semana epidemiológica.
- Atenciones de la semana anterior.
- Promedio de atenciones de las últimas cuatro semanas.
- Promedio de atenciones de las últimas ocho semanas.
- Atenciones registradas hace 52 semanas.

## Modelo predictivo

Se utiliza un árbol de decisión optimizado mediante validación temporal y búsqueda de hiperparámetros.

**Me
