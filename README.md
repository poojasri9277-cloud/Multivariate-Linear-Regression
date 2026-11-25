# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>
Import the required libraries such as NumPy and Scikit-learn.

### Step2
<br>
Load the dataset and separate the input features (X) and output variable (Y).


### Step3
<br>
Split the dataset into training and testing data.

### Step4
<br>
Train the Multivariate Linear Regression model using the training data.


### Step5
<br>
Predict the output using the testing data and display the predicted results.

### Program:
devolped by P.Pooja sri
reg.no 26018336

### import pandas as pd
### from sklearn import linear_model
### df = pd.read_csv("carsemission.csv")
### X = df[['Weight', 'Volume']]
### y = df['CO2']
### regr = linear_model.LinearRegression()
### regr.fit(X, y)
### print('Coefficients:', regr.coef_)
### print('Intercept:', regr.intercept_)
### input_data = pd.DataFrame({'Weight': [3300], 'Volume': [1300]})
### predictedCO2 = regr.predict(input_data)
### print('Predicted CO2 for the corresponding weight and volume:', predictedCO2)

## Output:
Coefficients: [0.00755095 0.00780526]
Intercept: 79.69471929115939
Predicted CO2 for the corresponding weight and volume: [114.75968007]

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
