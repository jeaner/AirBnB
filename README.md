# AirBnB
Machine learning on AirBnB user activity data to predict destination countries.


## Projectect Summary
### Please go through my Presentation.pdf to view my project summary
### 0) Exploratory Data Analysis
EDA was performed on the training data to see what the relationships looked like between data.
I explored how age might effect destinations and how gender might effect destinations.

### 1) Data Engineering
I made new data points based on the original data.
I explored the time between bookings and account creation.
I simplified the complex data from user's sessions on the airbnb site by making dummy variables for each user ID.

### 2) Data Cleaning
I cleaned the data about user age by using an xgboost predictor to fill in the NA data points

### 3) Data Split
I split the data into train, validation, and test sets. Because my data was so large and my computer does not have the best resources available, I had to make this it's own environment that I could then wipe and reload what was needed in the next notebook.

### 4) Train
I used XGBoost as my machine learning model. 
I explored the best hyperparameters.
I trained the final model and predicted the top 5 countries for each user

### 5) Final
This is just an extra R file because my jupyter notebook experienced a bug that wouldn't output graphics. 
I only used this to make graphics for my presentation.
