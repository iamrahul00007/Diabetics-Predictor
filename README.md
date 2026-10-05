# Diabetics-Predictor

---

# 🩺 Diabetes Classification using Support Vector Classifier (SVC)

## 📌 Overview
This project builds a machine learning model to classify whether a patient is diabetic or not, based on medical diagnostic features. The model uses **Support Vector Classifier (SVC)**, a powerful algorithm for binary classification tasks.

## ⚙️ Workflow
1. **Data Preprocessing**
   - Train-test split for model evaluation
   - Feature scaling using `StandardScaler`
2. **Model Training**
   - Support Vector Classifier (SVC) applied on scaled data
3. **Evaluation**
   - Accuracy score calculated on test data
   - Confusion matrix and classification report for deeper insights

## 📊 Results
The SVC model achieves competitive accuracy and demonstrates balanced performance across precision, recall, and F1-score. This makes it suitable for medical prediction tasks where minimizing false negatives is critical.


## 🌐 Future Work
- Deploy the model as an API using **FastAPI** or **Flask**
- Add a simple web interface for user-friendly predictions
- Compare performance with other classifiers (Random Forest, XGBoost)

---
