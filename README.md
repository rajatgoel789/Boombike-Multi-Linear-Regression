# BoomBikes Linear Regression Assignment
> This is a programming assignment wherein I build a multiple linear regression model for the prediction of demand for shared bikes


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


<!-- You don't have to answer all the questions - just the ones relevant to your project. 

-->
## Conclusions
- 1. R-sqaured value of train set is 82.07%  and the test set has the value of 79.78% which signifies the model accurately signifies the variance and it is a good model.

2. Our developed MSE is almost 0 on both train and test data set. We used P values and Vif for selection of the features. RFE is also conducted initially for automated variable selection.

3. We can conclude the bike demands is dependent on the actual temperature and the whether it is workday or not. Moreover demands on the winters are more as compared to summer and spring. It is also observed that there is more demand in the months of Oct and Sept. 

4. Overall these interpretation helps to derive meaningfull insigts in the bike rental demand and behaviour of the people. One of the recommendation based on our model is that there should be aggresive marketting in Summer and Spring to boost the demand. Rentals were more in 2019 than 2018 which suggests that over time more people would be exposed by time and there has to a strong analysis done to retain the repeat customers.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.7
- Pandas, numpy and sklearn
- stats module

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->




## Contact
Created by [@rajatgoel789] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->