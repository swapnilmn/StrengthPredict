# StrengthPredict

# StrengthPredict: Concrete Compressive Strength Prediction using Regression Models

This project explores the prediction of concrete compressive strength using various regression techniques, including linear regression with normal equations, gradient descent methods, and polynomial regression models. It was developed as part of the ID5030 - Machine Learning for Engineering and Science Applications course.


## Project Overview

The aim of this project is to implement and compare different regression models for predicting the compressive strength of concrete. The project evaluates the effectiveness of linear regression models, both with and without regularization, as well as the impact of feature expansion through quadratic and cubic models. Various gradient descent techniques are also explored to optimize the regression models.

## Project Structure

### Assignments

1. **Assignment 1: Linear Regression with Scikit-Learn**
   - Implemented a linear regression model using Scikit-Learn.
   - Evaluated the model using Mean Squared Error (MSE) and R-squared metrics.
   - Applied the model to the Concrete Compressive Strength Dataset and analyzed the results.

2. **Assignment 2: Linear Regression with Normal Equations**
   - Solved linear regression using the normal equations method.
   - Introduced L2 regularization and compared its effect on model performance.
   - Extended the model to quadratic and cubic regression models to understand the impact of feature expansion.

3. **Assignment 3: Gradient Descent and Its Variants**
   - Implemented linear regression using various gradient descent methods (batch, stochastic, mini-batch).
   - Compared custom Python implementations with PyTorch's gradient descent.
   - Explored advanced techniques like Gradient Descent with Momentum and Nesterov Accelerated Gradient Descent.

### Notebooks

- **1_regression_with_sklearn.ipynb**: Implementation of linear regression using Scikit-Learn.
- **2_Regression_with_nomral_equations_(Linear,_Quadratic_and_Cubic_model).ipynb**: Implementation of normal equations with feature expansion.
- **3_Regression_with_gradient_descent_and_variants_of_Gradient_Descent.ipynb**: Detailed implementation of gradient descent variants.

## Dataset

The project uses the [Concrete Compressive Strength Dataset](https://archive.ics.uci.edu/ml/datasets/concrete+compressive+strength), which includes 1,030 samples with 8 features representing concrete ingredients and age. The target variable is the compressive strength of the concrete in megapascals (MPa).

## Results

- **Linear Regression (Scikit-Learn)**: Achieved an MSE of 93.62 and an R-squared value of 0.64 on the test set.
- **Normal Equations**: Improved model performance with L2 regularization, achieving an MSE of 93.22 and an R-squared of 0.61.
- **Quadratic Model**: Significant improvement with an MSE of 61.92 and R-squared of 0.89, demonstrating the effectiveness of feature expansion.
- **Gradient Descent Variants**: Implemented and compared the performance of batch, stochastic, and mini-batch gradient descent methods, along with momentum-based optimizations.

