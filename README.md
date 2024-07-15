# Heart_Disease_Prediction_Project

Overview:- 
This project involves predicting whether a person has heart disease using a Logistic Regression model. The model has been evaluated using various metrics to ensure 
its effectiveness and reliability.

Model and Metrics:- 

1) Logistic Regression Model:
  - A Logistic Regression model was developed to predict the presence of heart disease.
2) Accuracy:
  - The model achieved an accuracy score of approximately 83%.
3) Evaluation Metrics:
  - Confusion Matrix: Used to evaluate the performance of the classification model.

F1-Score: Greater than 80% for both test and train datasets, indicating a good balance between precision and recall.
AUC-ROC: Also greater than 80% for both test and train datasets, demonstrating the model's ability to distinguish between classes.
Feature Importance:

Determined the importance of various features using the SMOTE function for both undersampled and oversampled data.

Data Handling
SMOTE (Synthetic Minority Over-sampling Technique):
Applied SMOTE to handle class imbalance by creating synthetic samples for the minority class.
Evaluated the model using both undersampled and oversampled data.
Getting Started
Prerequisites
Python 3.x
Jupyter Notebook or any Python IDE
Required libraries: pandas, numpy, scikit-learn, imbalanced-learn, matplotlib, seaborn
