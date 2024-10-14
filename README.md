# 📱 Detector de Spam SMS 🕵️‍♂️

## 🌟 Descripción del Proyecto

Este proyecto implementa un detector de spam para mensajes SMS utilizando técnicas avanzadas de procesamiento de lenguaje natural y aprendizaje profundo. Nuestro objetivo es proporcionar una herramienta precisa y fácil de usar para identificar mensajes de texto no deseados.

## 🚀 Características Principales

- 📊 Preprocesamiento de texto y extracción de características
- 🧠 Generación de embeddings utilizando DistilBERT
- 🤖 Clasificador de spam basado en redes neuronales
- 🖥️ Interfaz de usuario intuitiva con Streamlit

## 🛠️ Tecnologías Utilizadas

- Python 3.x
- 🐼 Pandas para manipulación de datos
- 🔤 NLTK para procesamiento de lenguaje natural
- 🤗 Transformers (DistilBERT) para generación de embeddings
- 🔥 PyTorch para el modelo de clasificación
- 📈 Scikit-learn para métricas de evaluación
- 🌊 Streamlit para la interfaz de usuario

## 🏗️ Estructura del Proyecto


SpamSMS/
│
├── data/
│   └── raw_data/
│       └── Spam_SMS.csv
│
├── models/
│   └── sms_spam_classifier/
│
├── src/
│   ├── features/
│   │   ├── sms_dataset.py
│   │   ├── text_processor.py
│   │   ├── feature_engineering.py
│   │   └── sms_embedding.py
│   │
│   ├── models/
│   │   └── distilbert_classifier.py
│   │
│   ├── utils/
│   │   └── time_decorator.py
│   │
│   ├── main.py
│   └── app.py
│
└── README.md


## 🚀 Cómo Empezar

1. **Clonar el repositorio:** Para comenzar, clona este repositorio en tu máquina local.

```bash

git clone

```

2. **Instalar Dependencias:** Instala las dependencias necesarias utilizando pip.

```bash

poetry install

```

3. **Ejecutar la Aplicación:** Por último, ejecuta la aplicación utilizando el siguiente comando.

```bash

streamlit run src/app.py

```

## 📝 Licencia

Este proyecto está bajo la Licencia MIT - mira el archivo [LICENSE.md](LICENSE.md) para más detalles.

## 🤝 Contribuir

Si deseas contribuir a este proyecto, por favor crea un fork del repositorio y envía un pull request con tus cambios. ¡Estamos abiertos a nuevas ideas y sugerencias!

