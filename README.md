# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Start the program.
### Step2
Write a program to perform multivariate regression in anaconda navigator.
### Step3
Run the program.
### Step4
Print the output.
### Step5
End the program

## Program:
```
#Program to find Univariate Linear Regression
#Developed by: SADHANA SHREE B
#Register number: 212223230177
import pandas as pd
from sklearn import linear_model
data=pd.read_csv("car.csv")
x=data[['Weight','Volume']]
y=data[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(x,y)
print('Coefficients:',regr.coef_)
print('Intercept:',regr.intercept_)
predictCO2=regr.predict([[3300,1300]])
print('predicted CO2 for the corresponding weight and volume',predictCO2)

```
## Output:
![Screenshot 2024-05-16 080449](https://github.com/SadhanaShreee/Multivariate-Linear-Regression/assets/144517664/0b16b7c3-2a4d-475a-af78-0ac8481df828)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
