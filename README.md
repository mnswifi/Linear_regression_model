# Linear_regression_model
## Regression Model Comparison: Linear Regression vs Random Forest
This repository contains a regression model that predicts an output variable based on input features. In this README file, we will compare the performance of the linear regression model and random forest model.

Dataset
The dataset used in this model is a randomly generated datasets. It consists of 1697 samples and 2 features.

Linear Regression Model
The linear regression model was trained using sklearn linear regression model. The model achieved a MSE of 2748.758381, and R-squared of 0.250793 on the test set.

Random Forest Model
The random forest model was trained using sklearn ensemble random forest regressor. The model achieved a MSE of 1396.872668, and R-squared of 0.619266 the test set.

Comparison
The performance of the linear regression model and random forest model was compared using mean squared error, R-squared. The MSE and R-squared of the random forest model was better than that of the linear regression model.

Getting Started
To run the regression model and compare the linear regression and random forest models, follow these steps:

Clone this repository.
Install the required libraries (pandas, seaborn, matplotlib, numpy, sklearn).
Run the Jupyter notebook (insert file name) to train and test the models.
Analyze the results and compare the performance of the models.

Conclusion
Based on the comparison of the linear regression and random forest models, we can conclude that the random forest model outperforms the linear regression model. However, further analysis and tuning may be required to optimize the model for specific use cases.
