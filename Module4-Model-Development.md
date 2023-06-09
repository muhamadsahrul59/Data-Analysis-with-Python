# Learning Objectives

* Describe how to process linear regression in Python
* Apply model evaluation using visualization in Python
* Apply polynomial regression techniques to Python
* Evaluate a data model by using visualization
* Describe the use of R-squared and MSE for in-sample evaluation
* Apply prediction and decision making to Python model creation

## Practice Quiz: Linear Regression and Multiple Linear Regression

Question 1: consider the following lines of code, what is the name of the column that contains the target values:

![3-1](https://user-images.githubusercontent.com/17474099/118960042-2cd52880-b963-11eb-85b9-28fd3c9c484e.png)

- A. [X] 'price'
- B. [_] 'highway-mpg'

Question 2: Consider the following equation:

![3-2](https://user-images.githubusercontent.com/17474099/118961442-9d307980-b964-11eb-8c6c-e700c234dec6.png)

The variable y is?

- A. [X] the target or dependent variable
- B. [ ] the predictor or independent variable
- C. [ ] the intercept

## Practice Quiz: Model Evaluation using Visualization

Question 1: Consider the following Residual Plot, is our linear model correct:

![3-3](https://user-images.githubusercontent.com/17474099/118967171-acb2c100-b96a-11eb-8c53-ce1907489bff.png)

- A. [X] Yes
- B. [ ] Incorrect

## Practice Quiz: Polynomial Regression and Pipelines

Question 1: What functions are used to generate Polynomial Regression with more than one dimension

- A. [ ] ![Web capture_5-4-2023_11617_www coursera org](https://user-images.githubusercontent.com/101655285/229883559-b1e435d5-0fb7-47c1-92ef-e5bb7dd5853d.jpeg)
- B. [X] ![Web capture_5-4-2023_11626_www coursera org](https://user-images.githubusercontent.com/101655285/229883778-47fcf672-3212-466e-8f53-fb4bccf084dc.jpeg)

## Practice Quiz: Measures for In-Sample Evaluation

Question 1: Of the following answer values, which one is the minimum value of R^2?

![3-6](https://user-images.githubusercontent.com/17474099/118988127-353c5c00-b981-11eb-90de-468f8efd67c3.png)

- A. [ ] 10
- B. [X] 0
- C. [ ] 1

## Lesson Summary

In this lesson, you have learned how to:

* **Define the explanatory variable and the response variable**: Define the response variable (```y```) as the focus of the experiment and the explanatory variable (```x```) as a variable used to explain the change of the response variable. Understand the differences between Simple Linear Regression because it concerns the study of only one explanatory variable and Multiple Linear Regression because it concerns the study of two or more explanatory variables.
* **Evaluate the model using Visualization**: By visually representing the errors of a variable using scatterplots and interpreting the results of the model.
* **Identify alternative regression approaches**: Use a Polynomial Regression when the Linear regression does not capture the curvilinear relationship between variables and how to pick the optimal order to use in a model.
* **Interpret the R-square and the Mean Square Error**: Interpret R-square (x 100) as the percentage of the variation in the response variable y  that is explained by the variation in explanatory variable(s) x. The Mean Squared Error tells you how close a regression line is to a set of points. It does this by taking the average distances from the actual points to the predicted points and squaring them.

## Model Development

[Model Development](https://github.com/1965Eric/IBM-DA0101EN-Analyzing-Data-with-Python/blob/main/DA0101EN-Model-development.ipynb)

## Graded Quiz: Model Development

Question 1: What does the following line of code do?

```
lm = LinearRegression()
```

- A. [X] Create a linear regression object
- B. [ ] Fit a regression object lm
- C. [ ] Predict a value

Question 2: What is the maximum value of ```R^2``` that can be obtained?

- A. [X] 1
- B. [ ] 0
- C. [ ] 10

Question 3: We create a polynomial feature as follows ```"PolynomialFeatures(degree=2)"```; what is the order of the polynomial?

- A. [ ] 0
- B. [ ] 1
- C. [X] 2

Question 4: Which statement is true about Polynomial linear regression?

- A. [ ] Polynomial linear regression is not linear in any way
- B. [ ] Polynomial linear regression uses linear Wavelets
- C. [X] Although the predictor variables of Polynomial linear regression are not linear the relationship between the parameters or coefficients is linear

Question 5: Consider the following equation:

![3-2](https://user-images.githubusercontent.com/17474099/119483275-152be480-bd55-11eb-8652-0a68fc0d09aa.png)

The variable y is what?

- A. [X] The target or dependent variable
- B. [ ] The intercept
- C. [ ] The predictor or independent variable
