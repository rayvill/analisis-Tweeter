# 🧠 Análisis de Sentimiento en Tweets - TextBlob

Este proyecto realiza un análisis de sentimiento en tweets usando Python. Utiliza un dataset de Kaggle con opiniones reales sobre aerolíneas de Estados Unidos, clasificadas como **positivas**, **negativas** o **neutrales**.

## 📂 Dataset

- Nombre: [Twitter US Airline Sentiment]
- Formato: CSV
- Columnas utilizadas:
  - `text`: Texto del tweet
  - `airline_sentiment`: Sentimiento real

## 🛠 Herramientas utilizadas

- Python 3
- pandas
- TextBlob
- wordcloud
- matplotlib
- seaborn
- scikit-learn
- re (expresiones regulares)

## 📊 Flujo del análisis

1. Carga del dataset
2. Limpieza de texto
3. Clasificación de sentimientos usando `TextBlob`
4. Comparación con etiquetas reales (`classification_report`)
5. Visualización con:
   - Matriz de confusión
   - Nube de palabras por sentimiento
6. Exportación del resultado a CSV

## 🚀 Instrucciones de uso

1. Clona este repositorio o descarga los archivos.
2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
