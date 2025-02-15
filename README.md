Titanic Survival Prediction - Machine Learning
Overview
This project predicts whether a passenger survived the Titanic disaster using a Naïve Bayes classifier. It includes:

Exploratory Data Analysis (EDA) to understand patterns
Model training with Naïve Bayes
Performance evaluation using Precision, Recall, F1-score, and Accuracy
Hyperparameter tuning to improve results
Dataset
The dataset used is the Titanic dataset from Kaggle. It contains passenger details such as age, fare, class, and survival status.
Exploratory Data Analysis (EDA)
EDA is performed to understand data distribution, handle missing values, and visualize survival patterns. Key steps include:

Handling missing values in Age, Cabin, and Embarked columns
Feature engineering (converting categorical variables to numerical)
Visualizing survival based on class, gender, and age
Model Training
Used Naïve Bayes Classifier
Split dataset into train (80%) and test (20%)
Evaluated using Precision, Recall, F1-score, and Accuracy
Hyperparameter Tuning
To improve model performance, applied:

GridSearchCV for best parameters
Feature selection for optimal input features
