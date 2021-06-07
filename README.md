 # Prediction_of_cab_booking 

## Basic details about problem : 

Cab booking system is the process where renting a cab is automated through an app throughout a city. Using this app,people can book a cab from one location to another location.  Being a cab booking app company, exploiting theunderstanding ofcab supply and demand could increase the efficiency of their service and enhance user experience by minimizing waiting time.

Objective of this work is to combine historical usage pattern along with the open data sources like weather data to forecast cab booking demand in a city.

## Data :

Hourly renting data span of two years is provided. Data is randomly divided into train and test set. We must predict the total count of cabs booked in each hour covered by the test set, using the information available prior to the booking period. 

Here train labels i.e. ‘Total_booking’ are provided in seperarte csv file & we must append to train dataset before building the model.

Descriptions of the columns present in the datasets as below.

- **datetime**-hourly date +timestamp 

- **season**-spring, summer, autumn, winter

- **holiday**-whether the day is considered a holiday

- **workingday**-whether the day is neither a weekend nor holiday

- **weather**-Clear , Cloudy,  Light Rain, Heavy temp-temperature in Celsius

- **atemp**-"feels like" temperature in Celsius

- **humidity**-relative humidity

- **windspeed**-wind speed

Total_booking-number of total booking

## Model building:

Following tasks are performed for building the efficient model & executing the project-

**Task1**:

1.Visualize data using different visualizations to generate interesting insights.

2.Outlier Analysis

3.Missing value analysis

4.Visualizing Total_booking Vs other features to generate insights

5.Correlation Analysis

**Task2**:

1.Feature Engineering

2.Grid search

3.Regression Analysis

4.Ensemble Model

