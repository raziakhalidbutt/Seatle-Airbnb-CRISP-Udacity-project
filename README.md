
# Seattle Airbnb Data Analysis

# Table of content
1. [Installation](#Installation)
2. [Motivation](#Motivation)
3. [File Description] (#FileDesciption)
4. [Results](#Results)
5. [Acknowledgements](#Acknowledgements)

<a name="Installation"></a>
# Installation

You need Anaconda distribution of python 3.* version. No additional libraries are required for this project.

<a name="Motivation"></a>
# Motivation

This project is part of Data Scientist Nanodegree Program from Udacity. The goal is to implement the CRISP-DM (Cross-Industry Standard Process for DATA Mining). For this Project I choose the Seattle Airbnb dataset to get some useful insights. Following are the 3 questions I looked in this dataset.

1. Analysis of room types, their percentages & price ranges.
2. Analysis of month wise room availably and corresponding prices ranges to answer what time is best to visit Seattle.
3.Neighborhood price Analysis to see which is the priciest neighborhood and which one is the best to choose.

<a name="FileDesciption"></a>
# File Description

There is one jupyter notebook file that answer the above questions. This file includes all the step done to answer these question.

**Seattle_airbnb_CRISP_project.ipynb**


There are three dataset files of Seattle Airbnb dataset that is downloaded from Kaggle (https://www.kaggle.com/airbnb/seattle)

* **listings.csv:** including full descriptions and average review score
* **reviews.csv:** including unique id for each reviewer and detailed comments
* **calendar.csv:** including listing id and the price and availability for that day

<a name="Results"></a>
# Results

Followings are the key findings:

* Entire home/apt category is the priciest on Airbnb with average price of $155 per night. However, on the other hand they account for 67% of all the available properties on Airbnb. By looking into this information people with less family member or solo travelers with low budget should plan their bookings much advance. 
* Most reviews are from the month of July, August and September which means people mostly visit Seattle in summer. It is interesting that although prices are higher in these months but still people prefer to visit Seattle during summer which is why higher demand increases prices. 
* Magnolia is the most expensive neighborhood
* Ballard is among the top 3 in terms of Location and among the top 4 in terms of Ratings; surprisingly it one of the three least pricy neighborhoods.  

You can find more in my [blog](https://medium.com/@raziakhalidbutt/a-look-into-seattle-airbnb-data-304263683050) 

<a name="Acknowledgements"></a>
# Acknowledgements

This dataset is part of Airbnb Inside, and the original source can be found [here](https://www.kaggle.com/airbnb/seattle).
