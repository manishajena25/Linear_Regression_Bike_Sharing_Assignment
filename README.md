# Linear Regression Bike Sharing Assignment
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market.


## Table of Contents
* Reading and Understanding the Data
* Data Quality Check
* Removing redundant & unwanted columns
* Creating Dummy Variables
* Splitting the Data using sklearn
* EXPLORATORY DATA ANALYSIS
* Rescaling the features
* Building a Linear Model
* Building Linear Model using 'STATS MODEL'
* Final Model Interpretation
* Assumptions
* Making Prediction Using Final Model
* Model Evaluation
* R^2 Value for TEST

## General Information
   A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

### Business Objective:
 - Which variables are significant in predicting the demand for shared bikes.
 - How well those variables describe the bike demands

 We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.


## Conclusions
The top 3 predictor variables that influences the bike booking are:

- Temperature (temp)
- weathersit (Light Snow)
- Year (yr)

The next best features that can also be considered are:
- season
- windspeed


## Technologies Used
- numpy - version 1.18.1
- pandas - version 1.0.1
- matplotlib - version 3.1.3
- seaborn - version 0.10.0
- statsmodels - version 0.11.0
- sklearn - version 0.22.1


## Contact
Created by Manisha Jena[@manishajena25] - feel free to contact me!
