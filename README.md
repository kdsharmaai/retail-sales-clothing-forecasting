# POC AI Projects

## Retail Sales Forecasting (Tabular Data, Sequential)

Dataset used: [Retail Sales: Clothing and Clothing Accessory Stores](https://fred.stlouisfed.org/series/RSCCASN) 

Total 334 monthly sale data available in database

TimeseriesGenerator used to generate batches of data, ratio 12:1 (X:y)

Tensorflow keras LSTM used as a layer with final dense layer with single neuron

Generated forecast of test data and compared with single graph with actual values for evaluation, Forecast and actual values are of very similar pattern

