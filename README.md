# **Weather prediction using Arima Model**
In this project, we analyze and forecast the average temperature values of six major cities in India, including Bangalore, Chennai, Delhi, Lucknow, Mumbai, and Rajasthan. We use time series analysis and machine learning techniques to predict the future average temperature values based on historical data. The data is loaded into data frames using pandas, and missing values are imputed with relevant values. The stationarity of the data is checked using the Augmented Dickey-Fuller (ADF) test, and auto Arima is used for finding the optimal parameters for the ARIMA model. Finally, the model is trained on the data, and predictions are made using the trained model.

## **Dataset**
We are using the Dataset named “Temperature _And_ Precipitation _Cities_IN” containing Nine csv files of different states named Bangalore, Delhi, Chennai , Rajasthan, Mumbai, Lucknow, Rourkela and Bhubaneshwar containing temperatures ranging from 1990 to 2022 and containing 5 columns named time, tavg, tmin, tmax and prcp and total 11894 rows

## **Hardware Requirements**
We strongly recommend a computer fewer than 5 years old.
Processor: Minimum 1 GHz; Recommended 2GHz or more 
Ethernet connection (LAN) OR a wireless adapter (Wi-Fi) 
Hard Drive: Minimum 32 GB; Recommended 64 GB or more 
Memory (RAM): Minimum 1 GB; Recommended 4 GB or above

## **Software requirements**
* Google Colaboratory => Colab, or "Colaboratory", allows you to write and execute Python in your browser, with Zero configuration required, Access to GPUs free of charge, Easy sharing
* Mozilla Firefox => Internet Browser 
* Discord => Discord is a VOIP and instant messaging social platform
* Python 3 => High-level General Purpose Programming Language
* Python Libraries => Libraries used in Python
     * Pandas -  Made for working with relational or labeled data both easily and intuitively.
     * Matplotlib – It’s a visualization library in Python for 2D plots of arrays.
     * StatsModels -  Python package that allows users to explore data, estimate statistical models, and perform statistical tests.
     * Pmdarima - pmdarima is a Python library typically used in Database and Time Series Database applications

## **Approach Used**
1. Load the dataset for each city into separate data frames using pandas. 
2. Check for missing values and impute them with relevant values. 
3. Check for stationarity of the data using the ADF test. 
4. Use auto Arima to find the optimal parameters for the ARIMA model. 
5. Split the data into training and testing sets. 
6. Train the ARIMA model on the training data. 
7. Make predictions using the trained model. 
8. Evaluate the model using the root mean squared error (RMSE). 
9. Calculate the percentage error based on the RMSE and the mean of the test data. 



 






