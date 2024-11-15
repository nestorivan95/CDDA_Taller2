# MINE-4101: Ciencia de Datos Aplicada - Taller 2

# CDDA_Taller2

Este repositorio contiene el código correspondiente al Taller 2 de la asignatura.

## Autores

- Santiago Najar
- Néstor Ramírez

## Descripción

El proyecto aborda el analisis de datos y debe ejecutarse en el orden establecido de 1 a 5.

## Contenido del Repositorio

El repositorio incluye los siguientes archivos y directorios:

- 1_entendimiento_preparacion.ipynb:
  - Comprensión y preparación de los datos necesarios para el proyecto. Incluye una exploración inicial de los datos, limpieza de los mismos, y un análisis exploratorio para identificar patrones, valores faltantes y posibles problemas. El objetivo es asegurarse de que los datos estén listos y en un formato adecuado para el entrenamiento del modelo.
- 2_entrenamiento_modelo.ipynb:
  - Proceso de entrenamiento del modelo de aprendizaje automático. Se detalla la selección de características, el ajuste de hiperparámetros y la elección del modelo adecuado para lograr la mejor precisión posible. Además, se incluyen métricas de evaluación inicial para medir el rendimiento del modelo durante el entrenamiento. 
- 3_analisis_resultados_modelo.ipynb:
  - Evaluación de los resultados obtenidos del modelo entrenado, enfocándose en la precisión, recall, y otras métricas relevantes para determinar su efectividad en el reconocimiento de productos en un supermercado. También se identifican los errores comunes y se analiza si el modelo cumple con los objetivos de precisión establecidos.   
- 4_generación_valor.ipynb:
  - Se discuten las formas de generar valor con el modelo desarrollado. Incluye estrategias para la implementación en un entorno de supermercado inteligente y su potencial impacto en la reducción de costos y mejora de la eficiencia. Además, se evalúan las posibles implicaciones financieras y de negocios al implementar el modelo. 
- 5_Insights.docx:
  - Evaluación detallada del modelo de automatización para un supermercado inteligente, analizando tanto sus fortalezas como los desafíos que enfrenta para su posible implementación. Se discuten los factores financieros y técnicos a tener en cuenta en el contexto colombiano, y se presentan recomendaciones para optimizar el modelo y el entorno de captura. Además, se sugieren alternativas intermedias que podrían ofrecer beneficios de automatización sin requerir una implementación total del sistema en su estado actual.
  
- dataset/: Carpeta que contiene los conjuntos de datos utilizados.
- sample_images/: Carpeta con imágenes de muestra relacionadas con el proyecto.

## Requisitos Previos

Antes de ejecutar los notebooks, asegúrate de tener instaladas las siguientes dependencias:

- Python 3.1
- pandas: Manipulación y análisis de datos.
- numpy: Operaciones numéricas y manejo de arrays.
- scikit-learn: Algoritmos de aprendizaje automático.
- matplotlib y seaborn: Visualización de datos.
- tensorflow y keras: Construcción y entrenamiento de modelos de aprendizaje profundo.
- nltk y spacy: Procesamiento de lenguaje natural.
- opencv-python y Pillow: Procesamiento de imágenes.
- requests y beautifulsoup4: Para realizar solicitudes HTTP y análisis de documentos HTML.
- sqlalchemy: Manejo de bases de datos.
- boto3: Interacción con servicios de AWS.
- xgboost y lightgbm: Algoritmos avanzados de boosting en aprendizaje automático.
- jupyter y jupyterlab: Ejecución y creación de notebooks interactivos.



