# Customer Churn Prediction using Machine Learning

A machine learning project that predicts whether a customer is likely to churn based on customer demographics, services, contract details, tenure, and billing information.

## 📌 Project Overview

Customer churn is an important business problem because retaining existing customers is often more valuable than acquiring new ones.

This project develops and compares multiple machine learning classification models to predict customer churn and identify factors associated with customer attrition.

## 🎯 Objectives

- Predict customer churn using machine learning.
- Preprocess numerical and categorical customer data.
- Compare multiple classification algorithms.
- Evaluate models using multiple performance metrics.
- Identify important factors associated with churn.
- Save the best-performing trained model for future predictions.

## 🗂️ Dataset

The dataset contains customer-level information including:

- Customer demographics
- Partner and dependent information
- Tenure
- Phone and internet services
- Online security and backup services
- Technical support
- Streaming services
- Contract type
- Payment method
- Monthly charges
- Total charges
- Churn status

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook
- Joblib

## 🤖 Machine Learning Models

The following models were trained and compared:

1. Logistic Regression
2. Random Forest
3. Gradient Boosting

## 🔄 Machine Learning Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
Data Preprocessing
      ↓
Train-Test Split
      ↓
Feature Scaling & Encoding
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Model Comparison
      ↓
Best Model Selection
      ↓
Model Saving
```

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

## 📈 Visualizations

The project includes:

- Model Performance Comparison
- Confusion Matrix
- ROC Curve
- Feature Importance

## 🏆 Best Model

The best model was selected based on ROC-AUC performance on the test dataset.

The trained pipeline was saved as:

```text
customer_churn_best_model.pkl
```

## 💡 Key Business Insights

The analysis indicates that customer churn can be influenced by factors such as:

- Contract type
- Customer tenure
- Monthly charges
- Payment method
- Internet service
- Availability of additional services

Month-to-month customers generally require greater attention from retention teams.

## 📁 Project Structure

```text
customer-churn-prediction/
│
├── customer_churn_data.csv
├── Customer_Churn_Prediction.ipynb
├── customer_churn_best_model.pkl
├── model_results.csv
├── best_model_results.csv
├── confusion_matrix.png
├── roc_curve.png
├── model_comparison.png
├── feature_importance.png
└── README.md
```

## 🚀 Future Improvements

- Build an interactive Streamlit web application.
- Deploy the model online.
- Add customer risk scoring.
- Implement hyperparameter tuning.
- Add automated model monitoring.
- Develop a customer retention recommendation system.

## 👩‍💻 Author

**Nisha Gour**

GitHub: `https://github.com/nishagour125-png`
