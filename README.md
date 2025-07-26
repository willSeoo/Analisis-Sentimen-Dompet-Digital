# Analisis-Sentimen-Dompet-Digital

# 🧠 Sentiment Analysis of E-Wallet Applications Using Machine Learning

This is my undergraduate thesis project focusing on **Sentiment Analysis** of user reviews on **digital wallet (e-wallet)** applications from the Google Play Store. The goal is to determine the most effective machine learning algorithm for sentiment classification.

## 📌 Project Overview

- **Topic**: Sentiment Analysis on Mobile App Reviews
- **Subject**: E-Wallet Applications (e.g., DANA, OVO, ShopeePay)
- **Objective**: To compare the performance of different ML algorithms in classifying user sentiments (positive/negative)
- **Language & Tools**: Python, Scikit-learn, Pandas, TF-IDF Vectorizer, Google Colab

## ⚙️ Methods Used

The following machine learning classifiers are implemented and compared:

- Naive Bayes
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Random Forest

The reviews are preprocessed with several NLP techniques such as:

- Lowercasing
- Normalization
- Stopword Removal
- Tokenization
- TF-IDF Vectorization

## 🧪 Dataset

- **Source**: Google Play Store review scraping
- **Size**: ~15000 user reviews
- **Format**: `.csv`
- **Labels**: Positive or Negative sentiment (manually labeled)

## 📊 Evaluation Metrics

Each model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## 🏆 Result

The comparison showed that:

> **Random Forest** achieved the highest accuracy in classifying user sentiments among the four algorithms tested.


## 🧠 Future Work

- Add more labeled data to improve accuracy
- Expand to multi-class sentiment (positive, negative, neutral)
- Deploy as a web-based sentiment analyzer






