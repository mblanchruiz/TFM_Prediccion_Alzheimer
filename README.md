# TFM: Desarrollo de un modelo predictivo para el diagnóstico del Alzheimer

Repositorio del Trabajo de Fin de Máster sobre la predicción del Alzheimer mediante modelos de aprendizaje automático aplicados a datos clínicos y biomarcadores.

## Descripción del proyecto

Este proyecto se ha basado en el uso de dos datasets con datos de pacientes con Alzheimer y otros grupos controles, uno de los datasets incluye datos clínicos y factores de riesgo, mientras que el otro incluye biomarcadores analizados por estudios de proteómica. Al primer dataset se la ha denominado Dataset Factores de Riesgo, y al segundo Dataset Biomarcadores.

Con el Dataset Factores de riesgo se ha realizado una tarea de clasificación para identificar a pacientes con la enfermedad (Alzheimer vs controles). Mientras que con el Dataset Biomarcadores, por un lado se ha realizado una tarea de clasificación diferenciando entre pacientes con Alzheimer, controles mayores y jóvenes, pacientes con Parkinson y pacientes con cáncer de mama, y por otro lado con este dataset se ha realizado también una tarea de regresión para predecir el pronóstico y avance de la enfermedad prediciendo los valores de la puntuación del MMSE (empleado en el diagnóstico de la enfermedad y que evalúa la gravedad del deterioro cognitivo).

Para el análisis de estos datasets se han aplicado técnicas de preprocesado de datos, selección de características (p-valor, ReliefF, RFECV), validación cruzada y la evaluación mediante métricas estándar. También se incluyeron análisis de interpretabilidad como la importancia de variables y análisis de residuos (en el caso de los modelos de regresión). Los modelos que se han empleado son Decision Tree, Random Forest, SVM, KNN, Logistic Regression, Ridge Regression, XGBoost y CatBoost.

## Estructura del repositorio

- `Dataset_Factores_Riesgo/` — Jupyter Notebooks con los análisis realizados para el Dataset Factores de Riesgo.
- `Dataset_Biomarcadores/` — Jupyter Notebooks con los análisis realizados para el Dataset Biomarcadores.
- `Figuras/` — Gráficos generados durante el análisis que se incluyen en la memoria del TFM.
- `Documentos del TFM/` — Memoria y presentación del TFM.
- `README.md` — Este archivo.

## Software y bibliotecas empleadas

- Python 3.11.5
- scikit-learn
- pandas, numpy
- matplotlib, seaborn
- CatBoost, XGBoost

## Nota

Los datasets utilizados no están incluidos en este repositorio, pero se puede acceder a ellos mediante los siguinetes enlaces:

- Dataset Factores de Riesgo: https://www.kaggle.com/datasets/rabieelkharoua/alzheimers-disease-dataset
  
- Dataset Biomarcadores: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi


## Autor

Este trabajo ha sido desarrollado por Mariam Blanch Ruiz como parte del Trabajo de Fin de Máster en Ciencia de Datos de la Universitat Oberta de Catalunya (UOC).
