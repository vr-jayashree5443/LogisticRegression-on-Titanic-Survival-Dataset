# LogisticRegression-on-Titanic-Survival-Dataset

## Overview
This project aims to predict the survival of passengers aboard the Titanic using the Logistic Regression model. The dataset used is the famous Titanic Survival Dataset, which contains information about passengers such as age, sex, fare, cabin, etc.

## Steps
1. **Import Libraries**: Necessary libraries such as pandas, numpy, matplotlib, seaborn, etc., are imported.
2. **Import the Dataset**: The Titanic dataset is loaded into the notebook.
3. **Data Analysis**: Data exploration, cleaning, and visualization are performed to understand the dataset better.
4. **Feature Scaling**: Scaling of numerical features is performed.
5. **Feature Encoding**: Encoding of categorical features like 'Sex' and 'Embarked' is done.
6. **Feature Selection**: Feature importance is determined using ExtraTreesClassifier.
7. **Choosing the Model**: Logistic Regression model is selected for prediction.
8. **Splitting the Data**: Data is split into training and testing sets using Stratified K-Fold Cross-Validation.
9. **Training the Model**: The Logistic Regression model is trained using the training dataset.
10. **Testing the Model**: The trained model is tested using the testing dataset.
11. **Performance Evaluation**: Performance metrics such as confusion matrix, classification report, and accuracy score are calculated to evaluate the model's performance.

## Exporting Model & Dataset
The trained Logistic Regression model is serialized using Pickle for future use. Additionally, the preprocessed dataset is available for further analysis or modeling.
