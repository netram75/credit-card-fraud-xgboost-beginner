# 🚀 XGBoost Beginner – Credit Card Fraud Detection

This project demonstrates an end-to-end implementation of XGBoost for detecting fraudulent credit card transactions on a highly imbalanced dataset.

🔗 **Kaggle Notebook:**  
https://www.kaggle.com/code/netramfaran/xgboost-beginner-credit-card-fraud

---

## 📊 Dataset Overview

- Total transactions: 284,807  
- Fraud cases: 492 (~0.17%)  
- Features: V1–V28 (PCA transformed), Time, Amount  
- Target variable: `Class`  
  - 0 → Normal transaction  
  - 1 → Fraudulent transaction  

This is a highly imbalanced binary classification problem.

---

## 🎯 Objective

Build a machine learning model capable of accurately detecting fraudulent transactions while properly evaluating performance on imbalanced data.

---

## 🛠 Techniques Used

- Stratified Train-Test Split
- Feature Scaling (Amount & Time)
- XGBoost Classifier
- ROC-AUC Evaluation
- Precision, Recall, F1-score Analysis
- Confusion Matrix
- Feature Importance Visualization

---

## 📈 Model Performance

| Metric | Value |
|--------|--------|
| Accuracy | 99.95% |
| Precision (Fraud) | 0.89 |
| Recall (Fraud) | 0.83 |
| F1-score (Fraud) | 0.86 |
| ROC-AUC | 0.9786 |

---

## 🧠 Key Insights

- Accuracy alone is misleading for imbalanced datasets.
- Precision and Recall are critical metrics in fraud detection.
- XGBoost performs strongly on structured tabular financial data.
- Even a baseline tuned model can achieve strong fraud detection performance.

---

## 📌 Conclusion

This beginner-friendly implementation demonstrates how to properly structure a real-world classification project using XGBoost, with emphasis on correct evaluation for imbalanced datasets.

---
