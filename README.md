# Clasificador de Mensajes Spam con Regresión Logística

Este proyecto implementa un modelo de clasificación binaria que predice si un mensaje de texto es **spam** o **no spam**, utilizando técnicas de procesamiento de lenguaje natural (NLP) y regresión logística con scikit-learn.

## Objetivo

Entrenar un modelo de machine learning capaz de identificar mensajes de spam en un conjunto de datos reales.

## Tecnologías utilizadas

- Python
- pandas
- scikit-learn
- matplotlib, seaborn
- TfidfVectorizer
- Regresión Logística

## Contenido del proyecto

- `SpamOrNotLogisticR.ipynb`: Notebook principal con todo el flujo de trabajo.
- `spam_dataset.csv`: Dataset utilizado, con mensajes etiquetados como spam o no spam.
- `README.md`: Este archivo.

## Proceso

1. **Carga y análisis exploratorio del dataset**
2. **Limpieza y vectorización del texto con TF-IDF**
3. **Entrenamiento de un modelo de regresión logística**
4. **Evaluación del modelo (matriz de confusión y precisión)**

## Resultados

El modelo ha alcanzado un **100 % de precisión** sobre el conjunto de prueba, mostrando una excelente capacidad de detección de spam. Se recomienda validación cruzada o pruebas con otros datasets para evaluar su generalización.

## Dataset

El dataset contiene mensajes etiquetados como spam (1) o no spam (0). Ha sido preprocesado y vectorizado para su uso en modelos de NLP.

*Hugo Perez*
