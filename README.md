# Fraud-Detection-using-Logistic-Regression
# 💳 Fraud Detection using Machine Learning (Logistic Regression)

## 📌 Project Overview

This project aims to detect fraudulent financial transactions using Machine Learning techniques.  
The model is trained on a real-world transaction dataset and focuses on handling **severely imbalanced data**.

We use **Logistic Regression** as the baseline model and analyze performance using precision, recall, F1-score, and probability threshold tuning.

---

## 📊 Dataset

- Source: Kaggle
- Dataset: Fraud Detection Dataset  
- Link: https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset

The dataset contains financial transactions with features such as:
- Transaction type
- Amount
- Account balances (before/after transaction)
- Fraud label (0 = not fraud, 1 = fraud)

---

## ⚙️ Workflow

1. Importing Libraries
2. Getting The Data
3. Cleaning The Data
4. Exploratory Data Analysis
5. Model training (Logistic Regression)
6. Evaluation using:
   - Precision, Recall, F1-score


---

## 🧠 Key Concepts Used

- Logistic Regression
- One-hot encoding

---

## 📈 Model Performance

The model was evaluated under different probability thresholds.

Best observed results:

- Precision (Fraud class): ~0.85–0.90  
- Recall (Fraud class): ~0.50–0.65  
- F1-score: ~0.60–0.66  

> Note: The dataset is highly imbalanced, so accuracy is not a reliable metric.

---
