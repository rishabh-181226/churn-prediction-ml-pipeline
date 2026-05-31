📊 Customer Retention Prediction (XGBoost + SHAP)
This project builds an end‑to‑end machine learning pipeline to predict customer churn using:

Data cleaning & preprocessing

Train/test split

ColumnTransformer + Pipeline

XGBoost with GridSearchCV

Feature importance

SHAP explainability

ROC‑AUC evaluation

🚀 Project Structure
Code
├── data/
├── notebooks/
├── src/
├── models/
├── requirements.txt
└── README.md
🔧 Technologies Used
Python

Pandas / NumPy

Scikit‑Learn

XGBoost

SHAP

Matplotlib

📁 Notebook
The main analysis is in:

Code
notebooks/01_retention_modeling.ipynb
It includes:

Data cleaning

Feature engineering

Model training

Hyperparameter tuning

SHAP explainability

ROC curve

📈 Results
Best model: XGBoost

Evaluation metric: ROC‑AUC

SHAP used to interpret feature contributions

🧠 Future Improvements
Add model comparison (Logistic, Random Forest, LightGBM)

Deploy model using FastAPI

Add MLflow tracking

Add unit tests
