# Coursera UW Machine Learning: Regression

Course can be found in [Coursera](https://www.coursera.org/learn/ml-regression)

Quiz answers for quick search can be found in my blog [SSQ](https://ssq.github.io/2017/08/19/Coursera%20UW%20Machine%20Learning%20Specialization%20Notebook/)

- Week 1: Simple Linear Regression:
    - Describe the input (features) and output (real-valued predictions) of a regression model
    - Calculate a goodness-of-fit metric (e.g., RSS)
    - Estimate model parameters to minimize RSS using gradient descent
    - Interpret estimated model parameters
    - Exploit the estimated model to form predictions
    - Discuss the possible influence of high leverage points
    - Describe intuitively how fitted line might change when assuming different goodness-of-fit metrics
    - [x] [Fitting a simple linear regression model on housing data](https://github.com/SSQ/Coursera-UW-Machine-Learning-Regression/tree/master/Programming%20Assignment%201) 
    
- Week 2: Multiple Regression: Linear regression with multiple features
    - Describe polynomial regression
    - Detrend a time series using trend and seasonal components
    - Write a regression model using multiple inputs or features thereof
    - Cast both polynomial regression and regression with multiple inputs as regression with multiple features
    - Calculate a goodness-of-fit metric (e.g., RSS)
    - Estimate model parameters of a general multiple regression model to minimize RSS:
      - In closed form
      - Using an iterative gradient descent algorithm
    - Interpret the coefficients of a non-featurized multiple regression fit
    - Exploit the estimated model to form predictions
    - Explain applications of multiple regression beyond house price modeling
    - [x] [Exploring different multiple regression models for house price prediction](https://github.com/SSQ/Coursera-UW-Machine-Learning-Regression/tree/master/Programming%20Assignment%202)
    - [x] [Implementing gradient descent for multiple regression](https://github.com/SSQ/Coursera-UW-Machine-Learning-Regression/tree/master/Programming%20Assignment%203)
    
- Week 3: Assessing Performance
    - Describe what a loss function is and give examples
    - Contrast training, generalization, and test error
    - Compute training and test error given a loss function
    - Discuss issue of assessing performance on training set
    - Describe tradeoffs in forming training/test splits
    - List and interpret the 3 sources of avg. prediction error
      - Irreducible error, bias, and variance
    - Discuss issue of selecting model complexity on test data and then using test error to assess generalization error
    - Motivate use of a validation set for selecting tuning parameters (e.g., model complexity)
    - Describe overall regression workflow
    - [x] [Exploring the bias-variance tradeoff](https://github.com/SSQ/Coursera-UW-Machine-Learning-Regression/tree/master/Programming%20Assignment%204)
    
- Week 4: Ridge Regression
    - Describe what happens to magnitude of estimated coefficients when model is overfit
    - Motivate form of ridge regression cost function
    - Describe what happens to estimated coefficients of ridge regression as tuning parameter ?? is varied
    - Interpret coefficient path plot
    - Estimate ridge regression parameters:
      - In closed form
      - Using an iterative gradient descent algorithm
    - Implement K-fold cross validation to select the ridge regression tuning parameter ??
    - [x] [Observing effects of L2 penalty in polynomial regression](https://github.com/SSQ/Coursera-UW-Machine-Learning-Regression/tree/master/Programming%20Assignment%205)
    - [x] [Implementing ridge regression via gradient descent](https://github.com/SSQ/Coursera-UW-Machine-Learning-Regression/tree/master/Programming%20Assignment%206)
    
- Week 5: Lasso Regression: Regularization for feature selection
    - Perform feature selection using ???all subsets??? and ???forward stepwise??? algorithms
    - Analyze computational costs of these algorithms
    - Contrast greedy and optimal algorithms
    - Formulate lasso objective
    - Describe what happens to estimated lasso coefficients as tuning parameter ?? is varied
    - Interpret lasso coefficient path plot
    - Contrast ridge and lasso regression
    - Describe geometrically why L1 penalty leads to sparsity
    - Estimate lasso regression parameters using an iterative coordinate descent algorithm
    - Implement K-fold cross validation to select lasso tuning parameter ??
    - [x] [Using LASSO to select features](https://github.com/SSQ/Coursera-UW-Machine-Learning-Regression/tree/master/Programming%20Assignment%207)
    - [x] [Implementing LASSO using coordinate descent](https://github.com/SSQ/Coursera-UW-Machine-Learning-Regression/tree/master/Programming%20Assignment%208)
    
- Week 6: Going nonparametric: Nearest neighbor and kernel regression
  - Motivate the use of nearest neighbor (NN) regression
  - Define distance metrics in 1D and multiple dimensions
  - Perform NN and k-NN regression
  - Analyze computational costs of these algorithms
  - Discuss sensitivity of NN to lack of data, dimensionality, and noise
  - Perform weighted k-NN and define weights using a kernel
  - Define and implement kernel regression
  - Describe the effect of varying the kernel bandwidth ?? or # of nearest neighbors k
  - Select ?? or k using cross validation
  - Compare and contrast kernel regression with a global average fit
  - Define what makes an approach nonparametric and why NN and kernel regression are considered nonparametric methods
  - Analyze the limiting behavior of NN regression
  - Use NN for classification
  - [x] [Predicting house prices using k-nearest neighbors regression](https://github.com/SSQ/Coursera-UW-Machine-Learning-Regression/tree/master/Week%206%20PA%201)
