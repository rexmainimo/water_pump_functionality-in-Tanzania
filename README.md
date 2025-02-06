# 🌊 Water Pump Functionality Prediction  

This project predicts the functionality of water pumps in Tanzania using machine learning. The dataset consists of numerical, categorical, date, and Boolean features.
A **Decision Tree and Random Forest Classifier** are trained using a **Scikit-Learn Pipeline** to preprocess data and optimize model performance.  
The best model is the Random Forest classifier!
---

## 📌 Project Overview  
The goal is to classify water pumps into three categories:  
1. **Functional**  
2. **Non-functional** and or **Functional but needs repair**  

I used **feature engineering, data preprocessing, and model evaluation techniques** to achieve high accuracy.

## 🔧 Installation  
Ensure you have **Python 3.x** and install the required dependencies:  

📊 Data Preprocessing
We use Scikit-Learn’s ColumnTransformer to process the dataset:

Numerical Features: Standardization, missing value imputation
Categorical Features: One-hot encoding
Date Features: Extracting year, month, week, and computing pump age
Boolean Features: Treated as binary values
The pipeline ensures automated and scalable preprocessing.

🔍 Model Training

I trained a Random Forest Classifier using GridSearchCV to find the best hyperparameters:

🎯 Model Performance
1. **Decision Tree Classifier**
    The model was evaluated using:
      ✅ Accuracy
      ✅ ROC-AUC Curve
      ✅ Precision-Recall Curve
      Accuracy: 0.7854 
      ROC AUC: 0.78  
2. **Random Forest Classifier** ✅
      The model was evaluated using:
      ✅ Accuracy
      ✅ ROC-AUC Curve
      ✅ Precision-Recall Curve
      Accuracy: 0.8277 
      ROC AUC: 0.90
   
Compared both models using ROC and precision curve and the Random Forest out performs Decision Tree in predicting funtionality of water pupms in Tanzania.
