# Bike_Rent_Prediction_

In this project, you are asked to combine historical usage patterns with weather data in order to forecast hourly bike rental demand.
we are using python and machine learning packages for this data science project. Linear reagression is the regression method used for prediction because its a continues variable.

Problem:
Bike sharing systems are a means of renting bicycles where the process of obtaining membership, rental, and bike return is automated via a network of kiosk locations throughout a city. Using these systems, people are able to rent a bike from one location and return it to a different place on an as-needed basis. Currently, there are over 500 bike-sharing programs around the world. The data generated by these systems makes them attractive for researchers because the duration of travel, departure location, arrival location, and time elapsed is explicitly recorded. Bike sharing systems therefore function as a sensor network, which can be used for studying mobility in a city.

Files Provided-
1. train.csv : Use this dataset to train the model. This file contains all the weather related features as well as the target variable “count”. Train dataset is comprised of first 18 months. 2. test.csv : Use the trained model to predict the count of total rentals for each hour during the next 6 months

calculating prediction score quality - 

The Evaluation metric for this project is Root Mean Squared Logarithmic Error (RMSLE). The RMSLE is calculated as: sqrt(mean(squared logarithmic errors))



