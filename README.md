# credit-card-fraud-detection-
#  Credit Card Fraud Detection

Detect fraudulent credit card transactions using machine learning with SMOTE, XGBoost, and SHAP explainability.

---

## 📁 Project Structure

---

## 📊 Dataset

- Source: [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 284,807 transactions
- Highly imbalanced (only 0.17% are fraud)

---

## 🧠 Features

- SMOTE oversampling to fix class imbalance
- Models used:
  - Logistic Regression (baseline)
  - Random Forest
  - ✅ XGBoost (best performance)
- SHAP to explain model predictions
- Gradio app for live prediction

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
pip install -r requirements.txt
jupyter notebook app.ipynb


