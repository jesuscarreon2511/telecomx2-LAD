# Telecom X - Predicción de Cancelación de Clientes (Churn)

## Descripción

Este proyecto desarrolla modelos de machine learning para predecir la cancelación de clientes en Telecom X.  

El objetivo es identificar los factores que influyen en el churn y construir modelos predictivos que permitan anticipar qué clientes tienen mayor probabilidad de cancelar sus servicios.

Este análisis forma parte del **Challenge Telecom X – Parte 2: Predicción de Cancelación (Churn)** del programa de Data Science LATAM.

---

## Objetivo del proyecto

Construir un pipeline de machine learning capaz de:

- Preparar los datos para modelado
- Analizar correlaciones entre variables
- Entrenar modelos predictivos
- Evaluar su desempeño
- Identificar los factores más importantes que influyen en la cancelación

---

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## Etapas del proyecto

### 🛠️ Preparación de los Datos

Se realizaron tareas de limpieza y transformación de los datos:

- Eliminación de columnas irrelevantes
- Codificación de variables categóricas
- Conversión de variables a formato numérico
- Preparación del dataset para machine learning

---

### 🎯 Correlación y Selección de Variables

Se analizó la relación entre las variables mediante:

- Matriz de correlación
- Visualizaciones exploratorias
- Análisis dirigido entre churn y variables relevantes

Esto permitió identificar factores asociados a la cancelación de clientes.

---

### 🤖 Modelado Predictivo

Se entrenaron dos modelos de clasificación:

- Regresión Logística
- Random Forest

Los datos fueron divididos en conjuntos de entrenamiento y prueba para evaluar el desempeño de los modelos.

---

### 📊 Evaluación del modelo

El desempeño se evaluó utilizando:

- Accuracy
- Precision
- Recall
- F1-Score
- Matriz de confusión

---

### 🔍 Importancia de Variables

Se analizó qué variables influyen más en la predicción de churn utilizando la importancia de variables del modelo Random Forest.

Entre los factores más relevantes se encontraron:

- Tiempo de contrato (Tenure)
- Gasto mensual
- Tipo de contrato
- Método de pago

---

### 📋 Conclusiones

El análisis muestra que los clientes con menor tiempo de permanencia y contratos mensuales presentan mayor probabilidad de cancelar el servicio.

Los modelos predictivos permiten identificar patrones que pueden ser utilizados por la empresa para implementar estrategias de retención y reducir la evasión de clientes.

---

## Estructura del repositorio
telecomx-churn-prediction
│
├── telecomx_parte2_ml.ipynb
├── datos_tratados.csv
└── README.md



---

## Autor

Jesús Carreón Morales

Proyecto desarrollado como parte del programa **Data Science LATAM – Challenge Telecom X**.
