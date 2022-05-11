# Project Name : Bike Sharing Assignment
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)


## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

- Background:
The project is being submitted as partial fulfilment of Advanced Certificate in Machine Learning and Deeping Learning course conducted jointly by IIIT, Bangalore and Upgrad.

- Business Problem: 
BoomBikes wants to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
	Which variables are significant in predicting the demand for shared bikes.
	How well those variables describe the bike demands
- Dataset Used:
day.csv: This dataset contains the count of rental bikes between years 2018 and 2019 in Capital bikeshare system with the corresponding weather and seasonal information.

## Conclusions
Independent variable having the largest absolute value for its standardized coefficient.
1)	Temperature (0.4923)
2)	LightSnow (-0.2856)
3)	Year (0.2338)
- Almost 68.6% of the bike booking was happening during Clear weather with a median of close to 5000 bookings (for two years).
- Almost 32% of the bike booking were happening in Fall with a median of over 5000 bookings (for two years). 
- Almost 97% of bike rentals are happening during non-holiday time.

## Technologies Used
Python 	3.8.8
Pandas 	1.2.4
Numpy 	1.20.1
Matplotlib 	3.3.4
Seaborn 	0.11.1
Sklearn	0.24.1
Statsmodels  0.12.2


## Acknowledgements
This project was inspired by IIT, Bangalore and Upgrad, Bangalore..
<p> References if any...</p>
- https://en.wikipedia.org/
- https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset
- Python Documentation
- Upgrad Study Material
- https://stackoverflow.com/


## Contact
Created by [@githubusername] 
