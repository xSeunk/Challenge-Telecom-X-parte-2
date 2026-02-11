# Challenge-Telecom-X-parte-2

Este notebook presenta un flujo de trabajo completo de ciencia de datos para identificar a los clientes con mayor riesgo de cancelar su servicio y proponer estrategias de retención basadas en datos.

## Resumen del Proyecto
El objetivo es predecir la fuga de clientes (Churn) utilizando datos históricos de cargos, servicios contratados y demografía. Se implementaron técnicas avanzadas de preprocesamiento y modelos de aprendizaje supervisado.

## Etapas del Análisis
* Limpieza de Datos: Eliminación de identificadores irrelevantes como customerID para evitar ruido en los modelos.
* Ingeniería de Características: Transformación de variables categóricas mediante One-Hot Encoding.
* Balanceo de Clases: Uso de la técnica SMOTE para generar datos sintéticos de la clase minoritaria, logrando un balance del 50/50.
* Estandarización: Aplicación de StandardScaler para normalizar las variables numéricas, asegurando un rendimiento óptimo en modelos lineales.
## Modelado:
* Regresión Logística: Modelo lineal para interpretación de coeficientes.
* Random Forest: Modelo de ensamble basado en árboles para capturar relaciones no lineales.
* Evaluación: Uso de métricas de Exactitud, Precisión, Recall y F1-score, junto con matrices de confusión.
