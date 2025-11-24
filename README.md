# Heart-disease-risk-prediction
This project builds a machine learning pipeline to predict the likelihood of heart disease using clinical health indicators.It include complete data preprocessing,exploratory dta analysis(EDA),model building,evealuation and feature interpreation,
The project was entirely in Google Colab using Python,Pandas,Scikit-learn,Matplotlib and Seaborn

Project files
Heart_Disease_risk_prediction- The full google colab notebook containing preprocessing ,EDA,ML Models, and results
heart.csv - Dataset used for training and testing the model

Project Description:
Heart disease is one of the leading causes of death worldwide.Early detection can significantly improve medical outcomes.The project uses machine learning algorithms to identify individuals who are likely to have heart disease based on sevaral key health factor such as:
-chest pain
-Maximum heart rate achived
-ST depression
-Exercise-include angina
-Cholestorel
-Age
-Resting blood pressure
-More clinical Indicator
The project demonstrates how traditional health datasets can be transformede into actionable predictions using machine learning.

Dataset:
Source:UCI Machine Learning Repository
Feature include both numeric and categorical variable
0-No heart disease
1-Heart disease present
Methods and Workflow
Data Preprocessing
-Handling Categorical variables using One-Hot Encoding
-Scaling Numeric columns with StandardScaler
-Train/test split(80%/20%)

Exploratory Data Analysis(EDA)
-Correlation heatmap
-Histogram of all features
-Categorical vs numerical analysis
-Feature importance visualization

Machine learining models
-Logistic Regression
-Random Forest Classifier

Evaluation Metrics
-Accuracy
-Precision
-Recall
-F1 Score
-Confusion Matrix
-Feature importance ranking
