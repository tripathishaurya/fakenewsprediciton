# 📰 Fake News Detection using Machine Learning

A beginner-friendly ML project that detects fake news using **Logistic Regression** and **TF-IDF Vectorization**, achieving over **98% accuracy** on real-world data 🧠📈.

---

## 📌 Overview

This project classifies news articles as either **Fake (0)** or **Real (1)** using **Natural Language Processing (NLP)** and **Machine Learning (ML)**. We use a combined dataset of political news and apply text preprocessing, vectorization, and classification.

---

## ✅ Features

- 🔍 Logistic Regression Model
- 🧹 Text Cleaning & Stemming
- 🧠 TF-IDF Text Vectorization
- 📊 Confusion Matrix, Classification Report
- 📈 Accuracy up to 98.4%
- 📦 Ready-to-run Python scripts

---

## 🧠 Tech Stack

- 🐍 Python
- 🤖 Scikit-learn
- 📊 Matplotlib
- 🐼 Pandas
- 🧹 NLTK (Natural Language Toolkit)

---

## 📂 Dataset Info

- **Fake.csv** – Contains fake news articles  
- **True.csv** – Contains real news articles  
- Merged and labeled:  
  - 🟢 `label = 1` → Real  
  - 🔴 `label = 0` → Fake  

Columns used:
- `title`
- `text`
- `subject`
- `label`

---

## 🚀 Workflow

1. 📦 Combine `Fake.csv` and `True.csv`
2. 🧹 Clean text (lowercase, punctuation, stemming)
3. ✨ Apply TF-IDF Vectorizer
4. 🧠 Train Logistic Regression Model
5. ✅ Evaluate with accuracy, F1-score, confusion matrix
6. 📊 Plot helpful graphs to visualize performance

---

## 🎯 Model Performance

- ✅ **Training Accuracy:** 99.0%
- 🧪 **Testing Accuracy:** 98.4%

```text
              precision    recall  f1-score   support

       Fake       0.99      0.98      0.99      4758
       Real       0.98      0.99      0.98      4474


##👨‍💻 Author
Made with ❤️ by Shaurya Tripathi


