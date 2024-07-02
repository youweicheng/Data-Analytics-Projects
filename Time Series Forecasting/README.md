# This project demonstrates the sales forecasting of Alcohol using LSTM. 

## The Key Tools I used:
1. MinMaxScaler from sklearn
2. LSTM from Pytorch

## The hyperparameters:
Parameters: {'hidden_size': 100, 'learning_rate': 0.01, 'epochs': 100}

## The Key Achievement: 
1. Developed a Deep Neural Network model using Pytorch (LSTM) to forecast alcohol sales.
2. Achieving a 99.9% mean square error (MSE) improvement.

# Improved LSTM model: Add dropout layers, bidirectional architecture and grid search into the LSTM model. 

## The best hyperparameters:
Best Parameters: {'hidden_size': 128, 'num_layers': 2, 'dropout': 0.1, 'learning_rate': 0.01, 'epochs': 100}

## The Key Achievement: 
1. Achieving a 98% mean square error (MSE) improvement.

## Findings:
1. The performance of a simple LSTM model is better than a complex LSTM model.

## Potential Reasons:
1. Overfitting:
Complex models with more parameters are prone to overfitting, especially with limited data. They might learn noise in the training data rather than generalizing well.
2. Data complexity:
If the underlying patterns in your data are relatively simple, a complex model might be unnecessary and could introduce noise in predictions.
3. Noise sensitivity:
Complex models might be more sensitive to noise in the data, while simpler models can be more robust.




