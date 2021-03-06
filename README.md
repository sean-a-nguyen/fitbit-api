# fitbit-api

![fitbit-logo](https://user-images.githubusercontent.com/69729732/112956660-8bb1ba80-90f5-11eb-8b9e-12b99eca5e92.png)


## What is an API? 
According to the Google definition, an API stands for an application programming interface in which it is a computing interface that allows users to interact between multiple software applications and gather information/data from it. A great analogy is when you go to a restaurant and order food with a waiter. You take a look through the menu and decide what to order. To put in the order, you tell your waiter what you would like to eat. The waiter then takes your order to the kitchen and the chef will cook whatever you ordered. The server will then bring the food out to you and now you can eat!

Think of the waiter as an API. The waiter takes your order (API takes your request) and the chef (the software application) will prepare your food (process your request) and give you your completed meal (data you requested).

## Introduction
I recently got a FitBit Inspire 2 as a gift and started using it to track my overall activity throughout the day. In recently starting a new job as night shift worker, I was curious to see any trends in my activity over 1 month, such as steps taken, calories burned, distance walked, heart rate and sleeping time, so I gathered the data using FitBit's API. 

Note, that these were the only metrics I decided to keep track of as FitBit allows you to track workouts and food as well. 

The overall goal of this analysis is to:
1. Practice using an API (My first time doing so)
2. Graph and depict statistical graphs
3. Undercover any underlying trends/insights (Am I getting enough sleep? activity?)

## Overview of files
1. [Accessing the API and Exporting the Data Template](https://github.com/sean-a-nguyen/fitbit-api/blob/main/Accessing%20the%20API%20and%20Exporting%20the%20Data%20Template.ipynb) - Shows how I accessed the API and exported the data in .JSON.
2. [Gathering the Data From the Exported JSON File](https://github.com/sean-a-nguyen/fitbit-api/blob/main/Gathering%20the%20Data%20From%20the%20Exported%20JSON%20File.ipynb) - Shows how I parsed the data to make it easier to analyze.
3. [Exploratory Data Analysis](https://github.com/sean-a-nguyen/fitbit-api/blob/main/Exploratory%20Data%20Analysis.ipynb) - Shows the visualizations of the data and reports findings and insights.  

## References
1. [FitBit API Documentation](https://dev.fitbit.com/build/reference/web-api/#:~:text=Fitbit%20provides%20a%20Web%20API,Fitbit%20Platform%20Terms%20of%20Service)
2. [List of different endpoints](https://dev.fitbit.com/build/reference/web-api/explore/)
3. [How to Access the API](https://www.youtube.com/watch?v=Ligsao33b94)
4. [Inspiration/Example](https://jessierayebauer.wixsite.com/jrbauer/single-post/2018/01/27/Tutorial-Explore-Your-Own-Fitbit-Data)
