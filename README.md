# credit-card-fraud-detection

#Project Overview
The project aims to predict whether a customer will default on their credit card payment based on various features. It involves building several machine learning models and tuning their performance using cross-validation and hyperparameter optimization.

#Dataset information
The dataset includes features related to customer demographics, payment history, and account balance. Although the exact dataset isn't specified in this extract, it typically involves features like the credit limit, payment status in previous months, and bill statements.

#Data Features
The features likely include a combination of numerical and categorical data, with preprocessing techniques like encoding and scaling applied.
#Data Preprocessing
Handling missing values (if any)
Scaling numerical features (to ensure models like Gradient Boosting work effectively)
Encoding categorical variables
Splitting the data into training and testing sets

#Model Building
Random Forest and Decision Tree models, which showed overfitting, as evidenced by a large difference between training and test accuracies.
Gradient Boosting: After cross-validation and hyperparameter tuning, this model achieved the highest performance, with a test accuracy of 87.1% and AUC of 0.87.
