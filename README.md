# Forecasting the Leading Indicator of a Recession: The 10-Year Minus 3-Month Treasury Yield Spread
Time series analysis and forecasting using classical econometric and novel deep learning methods

In this research paper, I have applied various econometric time series and two machine learning models to forecast the daily data on the yield spread − the difference between the 10-year Treasury yields and the 3-month Treasury bills. First, I decomposed the yield curve into its principal components, then simulated various paths of the yield spread using the Vasicek model. After constructing univariate ARIMA models, and multivariate models such as ARIMAX, VAR, and Long Short Term Memory (LSTM), I calibrated the root mean squared error (RMSE) to measure how far the models’ results deviate from the current values. Through impulse response functions, I measured the impact of various shocks on the difference yield spread. The results indicate that the parsimonious univariate ARIMA model (RMSE = 0.05185) outperforms the richly parameterized VAR method (RMSE = 0.4648), and the complex LSTM with multivariate data performs equally well as the simple ARIMA model.

The link to the pre-print is:
https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3687851
