## Heart Disease Prediction

This project uses various machine learning models to predict the likelihood of a **DEATH_EVENT** (i.e., death due to heart failure) based on patient health data. The objective is to compare different classifiers for medical prediction tasks.

## Dataset

The dataset used is `dataset.csv`, which contains medical information of patients, including features such as:

- age  
- anaemia  
- creatinine_phosphokinase  
- diabetes  
- ejection_fraction  
- high_blood_pressure  
- platelets  
- serum_creatinine  
- serum_sodium  
- sex  
- smoking  
- time  
- DEATH_EVENT (Target variable)

## Models Used

The following machine learning models were trained and evaluated:

- Gaussian Naive Bayes  
- Logistic Regression  
- XGBoost Classifier  
- Random Forest Classifier  
- Neural Network (Simple binary classifier)

## Evaluation Metrics

Each model is evaluated based on:

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

Visualizations of the confusion matrices for each model are also provided.

## Libraries Used

- `pandas`, `numpy` – Data manipulation  
- `matplotlib`, `seaborn` – Data visualization  
- `scikit-learn` – Machine learning models and evaluation  
- `xgboost` – Extreme Gradient Boosting classifier  
- `tensorflow`, `keras` – Deep learning (Neural Network)

