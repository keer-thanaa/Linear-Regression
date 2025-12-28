# Linear Regression - Diabetes Prediction

## What is Linear Regression?

Linear Regression is a **supervised learning algorithm**, where the dataset contains both **features (inputs)** and **labels (outputs)**. The objective of linear regression is to establish a relationship between the features and the label, which we assume to be **linear**.

### Terminology: Weights

**Weights** represent the importance of each feature. They indicate how much a particular feature contributes to the final output. A higher weight means the feature has a stronger influence on the prediction.

Overall, the label (`y`) can be expressed as the **sum of each feature multiplied by its corresponding weight**.

### Error and Objective

The error can be represented as:

error = w^T * x - y

The main goal of linear regression is to **minimize this error** so that the predicted values are as close as possible to the actual labels.

### Equation of the Line

The linear regression model can be written as:

y = w^T * x + b


Here:

- `w` represents the **weights** of the features  
- `x` represents the **feature values**  
- `b` is the **intercept**

### Intercept

The **intercept** is the value of the output when all feature values are zero. It shifts the regression line up or down to better fit the data.

---

## Equation of the Line (for this problem)

From the trained linear regression model, the equation of the line is:

y = 151.3456
+ 37.9040 * age
- 241.9644 * sex
+ 542.4288 * bmi
+ 347.7038 * bp
- 931.4888 * s1
+ 518.0623 * s2
+ 163.4200 * s3
+ 275.3179 * s4
+ 736.1989 * s5
+ 48.6707 * s6

Here:

- `y` is the predicted diabetes progression  
- The constant term **151.3456** is the **intercept**  
- The remaining values are the **weights of the corresponding features**

---

## Interpretation of a Weight (Example: Age)

The weight of the **age** feature is **37.9040**.  

This means that **for a one-unit increase in the age feature**, keeping all other features constant, the predicted diabetes progression **increases by approximately 37.9 units**.  

So, age has a **positive impact** on the prediction, indicating that higher age contributes to a higher predicted diabetes progression in this model.

