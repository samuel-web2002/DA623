# DA623
Explanation of Polynomial Regression using Gradient Descent

1. Function to generate sample data for polynomial regression
Purpose: This function generates synthetic data for polynomial regression.
Parameters: It takes a seed value to ensure reproducibility.
Output: Random data points are generated based on a polynomial equation, the degree of which is provided by the user.
Example: For instance, with a degree of 2, the function generates data points following the equation 
𝑦= 1.5𝑋^2 + noise.

2. Function to perform polynomial regression using gradient descent
   Purpose: This function implements polynomial regression using gradient descent.
Parameters: It takes the input data 𝑋 and labels 𝑦, degree of the polynomial, learning rate, and number of epochs.
Output: The function iteratively updates model parameters (theta) using gradient descent and returns the final parameters along with the gradient history and MSEs over epochs.
Gradient Descent: It computes gradients, updates theta, and calculates MSE at each epoch.
3. Function to add polynomial features to input data
Purpose: This function adds polynomial features to input data to prepare it for polynomial regression.
Parameters: It takes the input data 𝑋 and the degree of the polynomial.
Output: Returns the input data with polynomial features up to the specified degree.

4. Function to calculate Mean Squared Error
Purpose: This function computes the Mean Squared Error (MSE) between predicted and actual values.
Parameters: It takes predicted values and actual labels.
Output: Returns the MSE value.

5. Function to compute gradients for gradient descent
Purpose: This function computes gradients for gradient descent.
Parameters: It takes the polynomial features, predicted values, and actual labels.
Output: Returns gradients for updating model parameters.

6. Function to update parameters using gradient descent
Purpose: This function updates model parameters (theta) using gradients.
Parameters: It takes current parameters, learning rate, and gradients.
Output: Returns updated parameters.

7. Function to plot the change in gradients over epochs
Purpose: This function plots the change in gradients over epochs to visualize the convergence of gradient descent.
Parameters: It takes the number of epochs and gradient history.
Output: Displays a plot showing the change in gradients over epochs.

8. Function to generate and plot predictions based on polynomial regression
Purpose: This function generates and plots predictions based on polynomial regression.
Parameters: It takes input data, labels, degree of the polynomial, learning rate, and number of epochs.
Output: Displays a scatter plot of original data points along with the fitted polynomial regression curve.

User Input and Execution
User Input: The user provides the degree of the polynomial.

Execution:
Sample data is generated based on the user's input.
Hyperparameters like learning rate and number of epochs are set.
Polynomial regression is performed, and predictions are generated and plotted.
