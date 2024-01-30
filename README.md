# SP500-Stock-Price-Prediction
# Description
This study uses multilayer neural network to predict the stock price and tests whether the stimulated prediction is aligned with the actual stock returns through mean squared error (MSE) value. Acquired from Yahoo Finance, S&P 500 stock data ranged from January 2002 to July 2019 are the sample for the study. Through comparing the MSE value obtained from multilayer neural network with those of other machine learning forecasting methods, random forest regression, gradient boosting, and support vector machine (SVM), the results demonstrate the former method to be the most effective.
# Neural Network Analysis of Amazon Stock Prices

This project includes a Jupyter notebook (`nn_amzn_stock.ipynb`) that demonstrates the use of neural networks to analyze and predict Amazon's stock prices.

## Overview

The `nn_amzn_stock.ipynb` notebook contains a detailed workflow for preprocessing stock price data, designing a neural network model, training the model on historical stock price data, and making predictions about future stock prices.

## Dataset

The dataset used in this notebook consists of historical stock prices for Amazon. It includes features such as the opening price, closing price, highest price of the day, lowest price of the day, and the volume of stocks traded.

## Dependencies

To run the notebook, you will need the following Python libraries:
- NumPy
- pandas
- matplotlib
- scikit-learn
- TensorFlow / Keras

Ensure that you have these libraries installed in your Python environment before executing the notebook.

## Usage

To use the notebook, follow these steps:
1. Clone the repository or download the `nn_amzn_stock.ipynb` file.
2. Open the notebook in JupyterLab or Jupyter Notebook.
3. Execute the cells in order to preprocess the data, build the neural network model, train the model, and make predictions.

## Model

The notebook includes a neural network model built using TensorFlow and Keras. The model's architecture, hyperparameters, and training process are explained in detail within the notebook.

## Results

The final section of the notebook presents the results of the model's predictions. It includes visualizations of the model's performance on the training and test data, as well as its predictions for future stock prices.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.


