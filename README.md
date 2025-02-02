
# Linear Regression with Scikit Learn

Linear regression is a simple yet powerful technique for predicting a target variable based on one or more input features. By understanding the relationship between these variables, we can make informed predictions and gain valuable insights from data.
## Objective

Creating an automated system to estimate the annual medical expenditure for new customers, using information such as their age, sex, BMI, children, smoking habits and region of residence.
## Importing the Libraries

All the libraries required for this project are as follows -

- Python 3.x
- scikit-learn
- numpy
- pandas
- matplotlib    
## Dataset

Download the dataset from the below link.

https://github.com/stedy/Machine-Learning-with-R-datasets

## Summary of Process

Data Collection and Preparation: We begin by gathering a dataset that includes both the input features and the target variable. The data is then cleaned and preprocessed to handle missing values, categorical variables, and other common data issues.

Exploratory Data Analysis (EDA): We perform EDA to understand the distribution and relationships within the data. This step includes visualizing correlations, identifying patterns, and selecting relevant features for the model.

Model Training: Using scikit-learn, we create a linear regression model and fit it to the training data. We tune hyperparameters and validate the model using cross-validation techniques to ensure it generalizes well to new data.

Model Evaluation: After training, we evaluate the model's performance using metrics such as R² score and mean squared error (MSE). We also visualize the model's predictions against actual values to assess its accuracy.

Model Deployment and Prediction: Finally, we deploy the trained model to make predictions on new, unseen data. This step demonstrates the practical application of linear regression in real-world scenarios.