# Bike-Sharing-Demand-Prediction
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, they have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
#### The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Pandas version: 2.2.0
- Matplotlib version: 3.8.3
- Seaborn version: 0.13.2
- Sklearn version: 1.4.1.post1
- Statsmodels version: 0.14.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusions
We have arrived at the final model (containing 10 variables) after few iterations where each iteration involved removal of variables with high p-value/VIF's. The final model was tested on the test data and was found to be performing well. Based on the final model,  following are the top 3 features contributing significantly towards explaining the demand of the shared bikes :
 - temp : As was also evident from the plots & correlation, temp is the feature with maximum impact on shared bikes demand.
 - light-rain : This is a dummy variable created from season and has a -ve coefficient. As expected as well, if it rains the bikes demand will go down. This behaviour is also seen from the bar-plot of weathersit against cnt.
 - yr : Since the bike-sharing systems are slowly gaining popularity, the demand for these bikes is increasing every year proving that the column 'yr' is a good variable for prediction.
 
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Contact
Created by [@zeebee48] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->