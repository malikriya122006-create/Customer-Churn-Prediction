# 📊 Customer Churn Prediction using Machine Learning

## 📌 Project Overview

Customer churn is a major challenge for subscription-based businesses, as retaining existing customers is often more cost-effective than acquiring new ones.

This project aims to predict whether a telecom customer is likely to churn based on customer demographics, account information, and service usage. Multiple machine learning models were trained and compared to identify the best-performing model. The final model was further interpreted using SHAP (SHapley Additive Explanations) to understand the factors influencing customer churn.

---

## 🎯 Objectives

- Analyze customer data to identify churn patterns.
- Build and compare multiple classification models.
- Select the best-performing model using hyperparameter tuning.
- Interpret model predictions using SHAP.
- Predict churn for new customer data.

---

## 📂 Dataset

**Dataset:** IBM Telco Customer Churn Dataset

The dataset contains customer demographic information, subscription details, billing information, and whether the customer has churned.

---

## 🛠️ Project Workflow

1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
   - Handling missing values
   - Label Encoding
   - One-Hot Encoding
   - Feature Scaling
4. Train-Test Split
5. Model Training
6. Hyperparameter Tuning using GridSearchCV
7. Model Evaluation
8. Model Explainability using SHAP
9. Saving the Best Model
10. Predicting Churn for New Customers

---

## 🤖 Machine Learning Models Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- XGBoost

The models were evaluated using standard classification metrics, and the best-performing model was selected.

---

## 📈 Model Evaluation Metrics

The following metrics were used to compare model performance:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

---

## 🔍 Model Explainability

SHAP (SHapley Additive Explanations) was used to interpret the predictions made by the final model.

Key insights obtained from SHAP include:

- Month-to-month contracts contribute significantly to customer churn.
- Customers with shorter tenure are more likely to churn.
- Fiber optic internet users show higher churn risk.
- Lack of Online Security and Tech Support increases churn probability.

---

## 🚀 New Customer Prediction

The trained model can predict churn for new customer records after applying the same preprocessing steps used during training.

The prediction includes:

- Churn / No Churn prediction
- Prediction probability

---

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- SHAP
- Joblib
- Jupyter Notebook

---

## 📁 Project Structure

```
customer_churn_project/
│
├── customer_churn_project.ipynb
├── README.md
├── requirements.txt
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── models/
│   ├── xgboost_customer_churn.pkl
│   ├── scaler.pkl
│   ├── ohe.pkl
│   ├── feature_names.pkl
│   ├── best_params.pkl
│   └── metrics.pkl
│
└── .gitignore
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Customer-Churn-Prediction.git
```

Move into the project directory:

```bash
cd Customer-Churn-Prediction
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Open the Jupyter notebook:

```bash
jupyter notebook customer_churn_project.ipynb
```

---

## 📌 Future Improvements

- Deploy the model using Streamlit or Flask.
- Build an interactive dashboard.
- Automate preprocessing using a Scikit-learn Pipeline.
- Experiment with additional ensemble models.

---

## 👨‍💻 Author

**Your Name**

GitHub: https://github.com/your-username