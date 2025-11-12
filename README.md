# 😃 Emotion Detection from X (Twitter) Tweets using Deep Learning and BERT

## 📘 Project Overview

This project focuses on classifying text data into six emotion categories using various neural network architectures. The **Emotion Dataset** was used to evaluate model performance across traditional and advanced NLP approaches.

---

## 🎯 Objectives

* Build multiple deep learning models to classify emotions in text.
* Compare performance of ANN, RNN, LSTM, GRU, and BERT-based architectures.
* Identify the most effective embedding and model combination for emotion recognition.

---

## 🧠 Models Evaluated

| Model                                                 | Training Accuracy |
| ----------------------------------------------------- | ----------------- |
| ANN (One Hot, Count Vectorization, Tf-Idf, Embedding) | 0.88–0.89         |
| RNN (Simple, Bi, Deep)                                | 0.89–0.91         |
| LSTM (Simple, Bi, Deep)                               | **0.92**          |
| GRU (Bi + Deep)                                       | **0.94**          |
| BERT (Transfer Learning, Fine-Tuned)                  | **0.92**          |

---

## ⚙️ Tech Stack

* **Languages:** Python
* **Libraries:** TensorFlow, Keras, Transformers, NumPy, Pandas, Matplotlib, scikit-learn
* **Models Used:** ANN, RNN, LSTM, GRU, BERT
* **Dataset:** [Kaggle – Emotions Dataset](https://www.kaggle.com/datasets/nelgiriyewithana/emotions)

---

## 📊 Results

Fine-tuned BERT, Bi-LSTM, and Deep GRU models achieved the highest accuracies, with GRU reaching 94%, significantly outperforming traditional ANN and RNN architectures.

---

## 🚀 Key Features

* Comparison of multiple NLP architectures on the same dataset
* Implementation of word embeddings and transfer learning
* Model performance tracking with accuracy metrics

---

## 🏁 Conclusion

This project demonstrates how deep learning and transfer learning models like BERT can significantly improve text emotion detection performance compared to traditional neural architectures.

