# Credit Card Default Prediction
![download (1)](https://user-images.githubusercontent.com/101682011/175274464-36c7c8b0-0cd0-48b9-9a15-238043d7ba4c.jpg)


## 1. Business Problem

The objective of this project is to predict which customer might default in coming months. 
The research aims at developing a mechanism to predict the credit card default beforehand and to identify the potential customer base that can be offered various credit instruments so as to invite minimum default.


## 2. Solution Strategy

Step 01: Data Description: Use statistics metrics to identify data distributions.

Step 02: Feature Engineering: Derive new attributes based on the original variables to better describe the phenomenon that will be modeled.

Step 03: Exploratory Data Analysis: Explore the data to find insights and better understand the impact of variables on model learning.

Step 04: Feature Selection: Selection of the most significant attributes for training the model.

Step 05: Machine Learning Modelling: Machine Learning model training.

Step 06: Hyperparameter Fine Tunning: hoose the best values for each of the parameters of the model selected from the previous step.

Step 07: Convert Model Performance to Business Values: Convert the performance of the Machine Learning model into a business result.

## 3. Top 3 Data insights

No. of defaulters have a higher proportion of educated people (graduate school and university)

Customers with high credit limits tend to pay the pay on time and hence are not defaulters.

Imbalance in the target class which is balanced using SMOTE

## 4. Machine learning models implemented

Logistic Regression, Decision Tree, Random Forest, KNN  Classifier

## 5. Model performance comparision

![image](https://user-images.githubusercontent.com/101682011/175272847-66c1637b-b6a4-47ec-8785-5ab1dbb395b4.png)

## 6. Conclusion
Logistic Regression had an imbalance in the recall score of about 83% for class 0 and 56% for class 1.

Performance on Decision Tree and Random Forest is comparatively better. Decision Trees and Random Forest have recall scores of 75%(class 0) , 49%(class 1) and 65%(class 0), 66%(class 1) respectively.

The features like credit limit , payment amount and bill amount are important features as per Random Forest and Decision tree algorithm.
