# Proyecto de Inteligencia Artificial

## Sistema Multiagente para Análisis de Productos Cosméticos

Este proyecto implementa una arquitectura multiagente compuesta por tres agentes especializados que trabajan de forma secuencial sobre un dataset de productos cosméticos.

## Agente 1: Limpiador

Responsable de la preparación y normalización de los datos.

Funciones:

* Carga del dataset.
* Limpieza de valores nulos.
* Normalización de nombres de columnas.
* Corrección de caracteres especiales.
* Conversión de tipos de datos.
* Generación del dataset limpio.

Archivo generado:

* cosmetics_limpio.csv

## Agente 2: Entrenador

Responsable del entrenamiento y evaluación de modelos de Machine Learning.

Funciones:

* Validación de la variable objetivo.
* Preparación de características.
* Entrenamiento de modelos.
* Validación cruzada.
* Selección automática del mejor modelo.
* Generación de métricas.

Modelos utilizados:

* Linear Regression
* Random Forest Regressor
* Gradient Boosting Regressor

Archivos generados:

* modelo_cosmetics.pkl
* metricas_agente2.txt

## Agente 3: Comunicador

Responsable de la interacción con el usuario mediante lenguaje natural.

Funciones:

* Construcción de un corpus basado en el dataset.
* Generación de embeddings.
* Implementación de una base vectorial FAISS.
* Recuperación de información mediante RAG.
* Uso de Transformers para generación de respuestas.
* Preguntas automáticas de prueba.
* Chat interactivo.

Tecnologías utilizadas:

* Sentence Transformers
* FAISS
* LangChain
* Hugging Face
* Qwen 2.5

## Objetivo

Demostrar un flujo completo de Inteligencia Artificial utilizando agentes especializados para limpieza de datos, entrenamiento de modelos y comunicación mediante RAG y lenguaje natural.
