Stock Price Prediction with LSTM
Overview
This Python script uses Long Short-Term Memory (LSTM) neural network model to predict stock prices. The process involves data retrieval, preprocessing, model training, performance evaluation, and visualization of the predictions.

Steps Data Retrieval: Historical stock price data for the given stock name, 'AAPL', is retrieved using the yfinance library.

Data Preprocessing: Additional features such as 5-day and 20-day moving averages are calculated and the data is split into training and test sets.

LSTM Model Training: LSTM model is defined with two LSTM layers and compiled with optimizer and loss function. The model is then trained using the training data for 50 epochs.

Performance Evaluation: Performance metrics such as Mean Squared Error, Root Mean Squared Error, Mean Absolute Error, R-squared, and accuracy are calculated for both training and test data.

Visualization: The model's predictions are plotted against the actual stock prices to provide a visual representation of the predictions.

Libraries Used:

1.pandas
2.numpy
3.yfinance
4.matplotlib
5.scikit-learn
6.TensorFlow

Accuracy results
For Apple : 93.717%
For Microsoft : 92.23%
