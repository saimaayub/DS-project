# Electricity consumption prediction for London.
This Project aims to predict electricity consumption in London households using smartmeters by considering weather variables.
## Research question.
To compare prediction accuracy for energy consumption of different ARIMA models and RNN model GRU(Gated Recurrent Units) by examining correlation between different weather parameters and energy consumption in London from 2011, Nov to 2014 Feb. 
## Project objectives.
•	To understand the impact of weather on energy consumption.
•	To analyse the relationship or correlation between electricity consumption and weather parameters in London.
•	To improve the accuracy of energy consumption forecast by using different ARIMA models.
## Data description.
The project utilizes smart meter London and weather data.
## Purpose of the Code
the main purpose of this code is to find out that given the optimized parameters how accurately the models predict future energy consumptin by taking into account weather variables.
## Outline of study
Energy consumption data is converted from halfhourly to daily data, merged with daily weather data.
then after evaluating the correlations among different variables to choose a variable as exogeneous variable that here is average daily temperature. then on the pre-processed data ARIMAX, SARIMAX and GRU model are applied. parameters of these models are optimized using grid search, ACF and PACF.
Then 80% of data is used for training purposes and remaining 20% is used for testing or validation.
At the end on the basis of eveluation metrics, MAE, MAPE and RMSE conclusions are drawn.

