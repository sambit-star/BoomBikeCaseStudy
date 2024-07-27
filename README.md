# BoomBike bike sharing Project
> This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- Provide general information about your project here.
- What is the background of your project?
  This is an assignment from Upgrad where we build a multiple linear regression model for the prediction of demand for shared bikes
- What is the business probem that your project is trying to solve?
  A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.The company wants to know:
  Which variables are significant in predicting the demand for shared bikes.
  How well those variables describe the bike demands 
- What is the dataset that is being used?
  Daily bike demands across the American market

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

1.  Season [Inference after analysis: Summer and winter has positive correlation with count- indicating Boombike can keep more bikes in the streets. Spring has a negative Correlation with count indicating lesser requirements]
2.	Month [Inference after analysis: September has a positive correlation with count while Januray and July are negatively correlated]
3.	Weekday[Inference after analysis: non-significant correlation with count]
4.	WeatherSit[Inference after analysis: value 3(Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds) and 4 (Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog) has negative correlation with count]
5.	Holiday[Inference for analysis: Holdiay has a negative correlation with count. People are not preferring holidays for cycling for some reason. Working days are more preferred.]
6.	WorkingDay[Inference for analysis: non-significant correlation with count and explained by holiday]
7.  R-squared score on the test set we derived a value : 0.8025684920603356
8.  “temp”, “Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds” and “year” contributes significantly towards demand


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- Python - version 3.0
- Jupyter - version 7.0.8
- pandas
- plotly
- numpy
- matplotlib
- seaborn
- sklearn.model_selection
- sklearn.preprocessing
- sklearn.feature_selection
- sklearn.linear_model
- statsmodels.api
- statsmodels.stats.outliers_influence

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

Give credit here.

- This project was inspired by Upgrad
- References if any...
- This project was based on [this tutorial](https://www.upgrad.com).

## Contact

Created by [@sambit-star] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->