# billboard-predictions
Predict Billboard chart debuts using MusicBrainz &amp; deep learning

# 🎶 Predicting Billboard Hot 100 Debut Rankings Using MusicBrainz & Deep Learning

This project uses the [MusicBrainz API](https://musicbrainz.org/doc/MusicBrainz_API) alongside the [Kaggle Billboard Hot 100 dataset](https://www.kaggle.com/datasets) to predict whether a newly released pop song will debut in the **Top 10**, **Top 25**, or **Top 50** of the Billboard Hot 100 within weeks of its release.

Developed and run in **Google Colab**, the notebook leverages metadata and historical chart data to train a neural network model for classification.

---

## 🚀 Features

- 🔄 Fetches song metadata using the MusicBrainz API
- 📊 Loads and processes historical Billboard chart data
- 🧠 Builds and trains a convolutional neural network (CNN) using TensorFlow/Keras
- 📈 Visualizes training history and prediction performance
- 🎯 Classifies songs into Top 10, Top 25, or Top 50 debut categories

---

## 🧰 Dependencies

All libraries used are pre-installed in Google Colab:

- `pandas`
- `numpy`
- `matplotlib`
- `tensorflow`
- `requests` (for MusicBrainz API)

To run locally, install the dependencies using:

```bash
pip install -r requirements.txt
