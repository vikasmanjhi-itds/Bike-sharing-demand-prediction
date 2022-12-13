# Bike-sharing-demand-prediction
Bike sharing demand prediction by using Supervised learning(Regresion Technic)

Problem Statement:

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.


Data Description:

The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.


Attribute Information:

• Date : year-month-day
• Rented Bike count - Count of bikes rented at each hour
• Hour - Hour of the day
• Temperature-Temperature in Celsius
• Humidity - %
• Windspeed - m/s
• Visibility - 10m
• Dew point temperature - Celsius
• Solar radiation - MJ/m2
• Rainfall - mm
• Snowfall - cm
• Seasons - Winter, Spring, Summer, Autumn
• Holiday - Holiday/No holiday
• Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)


Data Pipeline:
● Exploratory Data Analysis (EDA): In this part we have done some EDA on the features to see the trend.
● Data Processing: In this part we went through each attributes and encoded the categorical features.
● Model Creation: Finally in this part we created the various models. These various models are being analysed and we tried to study various models so as to get the best performing model for our project.


Observations:
● Observation 1: In the Model Evaluation Matrices table, Linear Regression, KNN is not giving great results.
● Observation 2: Random forest & GBR have performed equally good in terms of adjusted r2.


Conclusions:

1.In holiday or non-working days there is demands in rented bikes.
2.There is a surge of high demand in the morning 8AM and in evening 6PM as the people might be going to their work at morning 8AM and returing from their work at the evening 6PM.
3.People prefered more rented bikes in the morning than the evening.
4.When the rainfall was less, people have booked more bikes except some few cases.
7.The Temperature, Hour & Humidity are the most important features that positively drive the total rented bikes count.
8.After performing the various models the Gradient Boosting and Extreme Gradient Boosting found to be the best model that can be used for the Bike Sharing Demand Prediction since the performance metrics (mse,rmse) shows lower and (r2,adjusted_r2) shows a higher value for the Gradient Boosting and Extreme Gradient Boosting models !
9.We can use either Gradient Boosting and Extreme Gradient Boosting model for the bike rental stations.


