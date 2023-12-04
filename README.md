# Airbnb_NYC_Price_Prediction
# New York City Airbnb Price Prediction
# Overview
This project aimed to build a model for predicting prices of Airbnb listings in NYC based on property attributes like room type, location, reviews etc. Both regression and classification techniques were applied.

# Data
The data was obtained from InsideAirbnb for listings in NYC in 2019. It contained the following relevant features:

room_type: listing space type e.g. 'Entire home/apt', 'Private room'
neighbourhood: area within NYC
reviews: number of reviews of the listing
price: target variable - price in dollars
# Methods
The modeling process included:
# Data exploration and visualization
Preprocessing - handling missing values and outliers
Regression models - Random Forest, Linear Regression
Classification models - XGBoost, Logistic Regression
# Results
The best regression model was Random Forest with a RMSE of 63.94
The top classification model was XGBoost with an accuracy of 71%
Location and room type were key factors influencing price
# Conclusion
Both regression and classification techniques were reasonably effective at modeling Airbnb prices. Regression provided interpretability while classification delivered higher accuracy. The models can help hosts price their properties appropriately.
