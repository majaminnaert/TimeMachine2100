# TimeMachine2100
An analysis subroutine for time machines: Predict destination country with best life expectancy in target year.

## What
Based on a dataset located at https://www.kaggle.com/kumarajarshi/life-expectancy-who, the work in this repository aims to predict the life expectancy of 5 selected countries in a target year using a linear regression model. It further aims to evaluate said model by relating the R² to the model complexity and by using test data, splitted from the aforementioned dataset before training the model. It should, among other neat features, show the predicted life expectancies of the chosen countries along with the prediction's reliability.

Optionally, a k-cross validation, p-values of predictors and f-test results will be available for further evaluation of model performance.

## Who
Members of Arai class at BeCode work solo on this. This repository is created, maintained and the code therein developed by Maja Minnaert.

## Why
This challenge will test my current skills at the aforementioned tasks and goals.

## When
Now. In one day. A sunny Friday the 18 of December 2020.

## Caveats
This research doesn't correct for expected changes in life expectancy due to COVID-19 and other future pandemics. Please refer to your time machine manufacturer for further help with this.

## How
Toolbox: VSCode, Git, GitHub, SciKit Learn, Pandas, Numpy, Matplotlib, Kaggle
Resources: Kaggle, BeCode course material, in-class helpchat, StackExchange and off course the whole bloody internet (and even the non-bloody internet!)

## Project todolist
-[ ] Download dataset
-[ ] Clone repository
-[ ] Pre-processing: filter out unneeded data
-[ ] Pre-processing: process data to useful format, shape, etc
-[ ] Analysis: create train/test
-[ ] Analysis: select model
-[ ] Analysis: fit and test model
-[ ] Display evaluation methods
-[ ] Determine desired output format from 'client'(coach)
-[ ] Apply validations: k-cross
-[ ] Apply validations: p-value of predictors
-[ ] Apply validations: f-test
-[ ] Repeat process for each country (goal = 5) (todolist will be edited as needed)
-[ ] Compare regressions and predictions over countries
-[ ] Write report
-[ ] Make presentable output of results
