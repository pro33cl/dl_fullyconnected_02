# 🧠 Predicción de Customer Churn con Redes Neuronales Fully Connected

Notebook: fulllyconnected_02.ipynb

📄 Descripción General

Este notebook desarrolla un flujo completo para la predicción de Customer Churn combinando modelos tradicionales y Deep Learning. Se realiza preprocesamiento, estandarización, análisis estadístico, selección de características con RandomForest y entrenamiento de una red neuronal MLP con métricas avanzadas como ROC y AUC.

📂 Contenidos del Notebook

1️⃣ Carga y preprocesamiento de datos

- Importación del dataset Customer Churn.csv.
- Limpieza y tratamiento de datos faltantes.
- Estandarización de variables numéricas.

2️⃣ Análisis exploratorio

- Distribución de la variable objetivo (churn).
- Análisis de Subscription Length y Customer Value. 
- Pruebas estadísticas (t-test, Mann–Whitney, point biserial).

3️⃣ Manejo del desbalance

- Oversampling con SMOTE.
- División train/test (33% test).
- Revisión de frecuencia de clases.

4️⃣ Selección de características

- Entrenamiento de RandomForestClassifier.
- Extracción de las variables más importantes.
- Reducción del dataset a las 7 mejores features.

5️⃣ Modelo de red neuronal Fully Connected

- Construcción de una MLP con Keras/TensorFlow.
- Uso de funciones de pérdida, optimizadores y métricas personalizadas (AUC).
- Entrenamiento y evaluación con ROC y AUC (objetivo > 90%).

🛠️ Tecnologías Utilizadas

- Python 3
- NumPy
- Pandas
- Matplotlib / Seaborn
- Scikit-Learn
- Imbalanced-Learn (SMOTE)
- TensorFlow / Keras
- SciPy

▶️ Cómo Ejecutar el Notebook
1. Clonar el repositorio:

- git clone <URL>
- cd <repo>

2. Instalar dependencias:

- pip install -r requirements.txt

3. Ejecutar:

- jupyter notebook fulllyconnected_02.ipynb

🎯 Objetivo del Proyecto

El objetivo es construir un modelo predictivo robusto que identifique clientes con alta probabilidad de cancelar el servicio. Se combina análisis estadístico, selección de características y Deep Learning para maximizar la capacidad predictiva (AUC > 0.90).

📬 Contacto

Proyecto desarrollado por Héctor Rubilar Valenzuela.
