**Early-stage Diabetes Prediction**

**Description:**
This repository contains code for predicting early-stage diabetes using various machine learning techniques and algorithm aggregation. The project aims to leverage data-driven approaches to identify potential indicators of diabetes onset in its early stages.

**Dataset:**
The dataset used for this project is available in the file diabetes_data_upload.csv.

**Data Preprocessing:**
The notebook Internship_Project.ipynb preprocesses the dataset by encoding categorical variables, splitting the data into training and test sets, and scaling the features.

**Training Models:**
The notebook trains multiple machine learning models, including Logistic Regression, Decision Tree, Neural Network, XGBClassifier, Random Forest, and a Voting Classifier. Each model is evaluated based on its accuracy score.

**Predicting Data:**
The notebook predicts the target variable using the trained models and generates confusion matrices to assess model performance.

**Conclusion:**
After comparing the models, Decision Tree, Neural Network, and Random Forest emerged as the best models for predicting diabetes in this dataset, with accuracies reaching up to 98.07%.
