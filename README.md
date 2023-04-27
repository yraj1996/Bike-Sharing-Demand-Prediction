# Bike-Sharing-Demand-Prediction

This Project aims to predict the demand for bike sharing services in Seoul, South Korea. Bike sharing services have become increasingly popular in recent years, providing an affordable and environmental friendly way to get around the city. However, bike sharing companies often struggle with balancing their inventory of bikes at each station, as demand for bikes can fluctuate greatly throughout the day.

To address this issue, the Seoul Metropolitan Government has provided data on the city's bike sharing system, including information on weather, time of day, and the number of bikes rented. This data has been used to build a machine learning model that predicts the number of bikes that will be rented at any given time.

The project was divided into several stages.

The first stage involved data inspection which included looking for missing values and duplicate values.

The next stage involved exploratory data analysis, where trends and patterns in the data were identified. Distribution of data was also studied.

Hypothesis Testing was performed on two hypothesis.

After this Feature selection and Preprocessing of data was done by converting categorical variables into numerical ones, splitting data and data scaling .

Furthur, various machine learning algorithms were tested on the split data that is trainig and test dataset, including Linear regression, Lasso regression, Ridge regression and Random forests classifier.

The performance of each model was evaluated using metrics such as root mean squared error and mean absolute error and R squared. The Random forests classifier model was found to be the most accurate.

Overall, the Seoul Bike Sharing Demand Prediction Project demonstrates the power of machine learning in predicting demand for bike sharing services. By accurately predicting demand, bike sharing companies can optimize their inventory and provide better service to their customers.


After performing every steps like data wrangling , EDA , data cleaning, data preprocessing, scaling and splitting of data and implementing some basic linear regression models on our dataset.

The following observations were made after analyzing the data :

* General trend is as the temperature increases number of bike rentals also increases.
Bike rental count decreases with increase in Humidity.
Bike Rentals are fairly invariable of Wind speed but a faint increase can be seen in the trendline.
Bike Rentals mildly increases with increase in Visibility
Sharp increase can be noted with increase in Dew Point temperature.
On an average, Rented bike counts increases with increase in Solar Radiation.
Decline in Bike Rentals is seen with increase in Rainfall.
Decline in Bike Rentals is seen with increase in Snowfall.
Least Rentals were observed in the month of December, January and February i.e. during winter seasons.
Highest Rentals were observed during the months of May, June, July i.e. during summer.
Sudden spike is seen between 7-9 AM and 5-7 PM. This is due to the office goers and students.
Rentals after midnight are more on weekends than weekdays.
Rentals during day is more on weekdays than weekends and sudden jump is also not witnessed during weekends.
Peak hours remain to be the same irrespective of the seasons.
Winters have least numbers of rentals followed by Spring, Autumn and Summer respectively.
Demand after 6 PM is marginally high during winters than other seasons.
Observations for all four seasons are fairly equal.
Observations for Holidays are very less compared to Non- Holiday observations.
Observations for Functioning days are very large and Non functioning day are very less.
Rented Bikes count is way more on working days than on Holidays. This might due to the usage of Rental Bikes for commuting to office.
After applying our regression models and Random forest classifier we found out around 60% variance capture for test dataset and we also find out the most important features in our model.
