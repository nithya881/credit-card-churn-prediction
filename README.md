# 💳 Credit Card Customer Churn Prediction

This project builds a machine learning model to predict whether a credit card customer is likely to **churn** or **remain active**, based on customer demographics, account information, and transaction behavior.

The project demonstrates an **end-to-end machine learning workflow**, including data preprocessing, model training, evaluation, and interpretation.

---

## 🎯 Problem Statement

Customer churn is a major concern for banks, as retaining existing customers is more cost-effective than acquiring new ones.

The goal of this project is to predict customer churn so that banks can take proactive steps to retain high-risk customers.

This is a **binary classification problem** with an **imbalanced dataset**.

---

## 📊 Dataset

- Source: Kaggle – Credit Card Customer Churn Dataset
- Total records: 10,127 customers
- Target variable: `Attrition_Flag`
  - Existing Customer
  - Attrited Customer

The dataset contains a mix of numerical and categorical features related to customer behavior and credit usage.

---

## 🧭 Approach

The project follows these steps:

1. Load and explore the dataset
2. Clean the data and remove irrelevant columns
3. Encode categorical features
4. Split data into training and testing sets
5. Train multiple machine learning models
6. Evaluate models using appropriate metrics
7. Select the best-performing model

---

## 🤖 Models Used

- Logistic Regression (baseline model)
- Logistic Regression with class weighting to handle imbalance
- 🌳 Random Forest Classifier (final model)

---

## 📈 Results

The Random Forest model achieved the best overall performance.

- Accuracy: **95%**
- Recall (Attrited Customers): **78%**

Confusion Matrix:[[252, 73],[ 22, 1679]]


This model provides a good balance between overall accuracy and the ability to detect churn customers.

---

## 🔑 Feature Importance

The most important features influencing churn were:

- Total transaction count
- Total transaction amount
- Change in transaction behavior
- Credit utilization ratio
- Months of inactivity

Transaction-related features were found to be the strongest indicators of churn.

---

## 🧠 Key Takeaways

- Accuracy alone is not sufficient for imbalanced datasets
- Recall is a critical metric for churn prediction
- Handling class imbalance improves model usefulness
- Tree-based models capture non-linear patterns effectively

---

## 🛠 Requirements

- Python 3.9+
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

Install dependencies using: pip install -r requirements.txt


---

## ▶️ How to Run

- Clone the repository
- Install dependencies
- Run the notebooks sequentially, starting from data loading and ending with evaluation

---

## 📌 Notes

- All preprocessing is performed in code
- No manual changes were made to the dataset
- The project is intended for learning and resume demonstration purposes

---

## 👤 Author

Nithya Bhat



