# visitor_prediction
Okinawa data visitor prediction:

This program expects car GPS probe data as input. Please provide the input csv to <2019-04_2019-08_GyokuSendo.csv>  which is expected to have the following fields (serial,tripcount,tlm_datage,lon,lat). 'tlm_datage' is provides current datetime (e.g 2009-01-01 12:30:20) . 
Two notebook scripts will then work on it.

1. Data Preparation (1_prepare_data.ipynb)

2. Prediction Model: Multiple Liner Regression (2_visitor_prediction.ipynb)
