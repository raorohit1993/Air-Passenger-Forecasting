# Air-Passenger-Prediction
To predict / forecast the number of passengers travelling using aeroplanes based on time series data. It is a typical Time Series Analysis problem.
 - Applied ADF and KPSS tests for dataset stationarity, applied Box-Cox Transformation to eliminate non-stationarity.

 - What is Stationarity?
A. any statistical model on a Time Series, the series has to be stationary, which means that, over different time periods,
a) It should have constant mean.
b) It should have constant variance or standard deviation.
c) Auto-covariance should not depend on time.

- Augmented Dickey–Fuller test is used to gives us various values that can help in identifying stationarity. The Null hypothesis says that a TS is non-stationary. It comprises of a Test Statistics & some critical values for some confidence levels. If the Test statistics is less than the critical values, we can reject the null hypothesis & say that the series is stationary. THE ADCF test also gives us a p-value. Acc to the null hypothesis, lower values of p is better.

- Trend & Seasonality are two reasons why a Time Series is not stationary & hence need to be corrected.
# Statistical Tests for Time Series Analysis.
- Time Series Decomposition with Error Trend Seasonality Model
- Trend Component shows the general growth/decline pattern.
- Seasonal Component shows any repetitive cycles in the time series.
- Residual Component is the error or noise that cannot be represented as Trend or Seaonality.
- Additive Model is used when the trend is more linear and the Trend and Seasonality Components are increasing/decreasing at a constant rate over time.
- Multiplicative Model is used when the Trend and Seasonality Components are increasing/decreasing at a non-linear rate over time.
- Holts Winter, ARIMA & SARIMA models.
 
- ARIMA(Auto Regressive Integrated Moving Average) is a combination of 2 models AR(Auto Regressive) & MA(Moving Average). It has 3 hyperparameters - P(auto regressive lags),d(order of differentiation),Q(moving avg.) which respectively comes from the AR, I & MA components. The AR part is correlation between prev & current time periods. To smooth out the noise, the MA part is used. The I part binds together the AR & MA parts.


