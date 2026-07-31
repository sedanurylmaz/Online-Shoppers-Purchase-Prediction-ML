# Online Shoppers Purchase Prediction

This project focuses on predicting whether an online visitor will complete a purchase based on session-level behavioral data from an e-commerce website.

The goal is to compare different machine learning algorithms, identify the most effective model, and analyze the impact of feature engineering and hyperparameter optimization on prediction performance.

## Dataset

The project uses the **Online Shoppers Purchasing Intention Dataset**, which contains information about user sessions, browsing behavior, traffic sources, and purchase outcomes.

Target variable:

- **Revenue**
  - True → Purchase
  - False → No Purchase

## Project Pipeline

- Data preprocessing
- Exploratory data analysis
- Feature selection using Recursive Feature Elimination (RFE)
- Feature scaling
- Training multiple classification models
- Hyperparameter tuning with GridSearchCV
- Model evaluation and comparison
- Model explainability using SHAP

## Models

The following models were implemented and evaluated:

- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors
- Gaussian Naive Bayes
- Gradient Boosting
- Multi-Layer Perceptron (MLP)
- XGBoost
- LightGBM

## Evaluation Metrics

The models were compared using multiple performance metrics including:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix
- Precision-Recall Curve

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- LightGBM
- SHAP
- Matplotlib
- Seaborn


## Future Improvements

Potential future work includes:

- Model deployment with FastAPI
- Docker containerization
- Experiment tracking with MLflow
- Building a real-time prediction API
- Developing an interactive Streamlit dashboard

---

Developed by **Sedanur Yılmaz**
