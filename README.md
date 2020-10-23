# Forecast-of-Minneapolis-St.-Paul-Temperature
Prediction of daily minimum temperature of twin cities
Minneapolis-st Paul is one of the coldest metropolitan areas in United States, where I have lived for the past seven years. I am interested in applying tensorflow to build a model used for predicting the daily minimum temperature of the twin cities area. The data source can be found on Minnesota Department of Natural Resources website: https://www.dnr.state.mn.us/climate/historical/daily-data.html?sid=mspthr&sname=Minneapolis/St%20Paul%20Threaded%20Record&sdate=2010-01-01&edate=por. A csv data file will be downloaded. It is dataset of daily minimum temperatures, daily maxium temperatures and other parameters in twin cities of Minnesota measured from 2010 to 2020 (October). Here I will use the daily minimum temperatureto to build a prediction model. TensorFlow will be used to build a neural network for training of the time series data and make a forecast, with combination of convolutional neural network, recurrent neural network and deep neural network. Mean absolute error is used to evaluate the model.

References:
1. Coursera Course by deeplearning.ai: Sequences, Time Series and Prediction
https://www.coursera.org/learn/tensorflow-sequences-time-series-and-prediction/home/welcome
2. Daily weather report of Minneapolis/St Paul Threaded Record:
 https://www.dnr.state.mn.us/climate/historical/daily-data.html?sid=mspthr&sname=Minneapolis/St%20Paul%20Threaded%20Record&sdate=2010-01-01&edate=por.
