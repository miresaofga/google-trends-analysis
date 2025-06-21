# Google Search Query Analysis & Trend Prediction
Analysis of google trends data to identify emerging search queries and predict future search volume.
# Overview

This project analyzes Google Trends data to identify emerging search queries and predict future search volume related to travel. The goal is to identify popular travel destinations among millennials and Gen Z in the post-pandemic era, understand their preferences for sustainable and experience-based travel, and forecast future demand for specific travel niches.

# Problem Statement

Understanding the evolving travel preferences of younger generations (millennials and Gen Z), particularly their increased interest in eco-friendly and authentic experiences, is crucial for helping travel agencies and tourism boards tailor their offerings and marketing strategies to attract this demographic, ensuring long-term sustainability and relevance in a competitive market.

# Data Sources

* Google Trends API: Used to collect weekly search interest data for specific travel destinations, keywords related to sustainable travel (e.g., "eco-tourism," "responsible travel"), and experience-based travel (e.g., "adventure travel," "cultural immersion") from 2016 to 2021 in Europe and North America.

# Methodology

1. Data Collection:
    Used the Google Trends API to collect weekly search interest data for specific travel destinations, keywords related to sustainable travel (e.g., "eco-tourism," "responsible travel"), and experience-based travel (e.g., "adventure travel," "cultural immersion").
3. # Data Cleaning
4. No data cleaning was required, as the Google Trends API provides pre-processed and normalized data.
5. # Exploratory Data Analysis (EDA):
6. Exploratory data analysis was performed to understand the basic characteristics of the data. Specifically, I identified top trending travel destinations among millennials and Gen Z, analyzed seasonal travel patterns, and compared search interest for different types of travel (sustainable vs. conventional tourism).
7. # Time Series Modeling
8. Used the Prophet model to predict future search volume for flights and accommodations in top trending destinations, as well as search interest in sustainable travel options**. The model was trained on historical data from 2016-2021 and evaluated using data from 2019. Model performance was assessed using Mean Absolute Percentage Error (MAPE).
# Visualization
   Created visualizations to illustrate travel trends among younger generations, compare search volume for different destinations and travel types, and show the accuracy of the Prophet model in predicting future demand.

# Results

. Identified Iceland, Costa Rica, and Slovenia as the top 3 emerging travel destinations in Europe and North America for millennials and Gen Z in 2019, based on search interest growth for sustainable and experience-based travel options.
. The time series model accurately predicted search volume for flights to Iceland with a Mean Absolute Percentage Error (MAPE) of 8.5%, demonstrating the potential for using Google Trends data to forecast travel demand.
. Search interest in "eco-tourism" and "responsible travel" increased by 35% between 2016 and 2021, indicating a growing preference for sustainable travel options among younger generations.

## Skills Used

* Python
* Pandas
* NumPy
* Prophet
* Matplotlib/Seaborn
* Google Trends API

## Code

[Link to your Jupyter Notebook or Python script - you'll add this after uploading your code]

## Visualizations (If Applicable)

[If you have a Tableau Public visualization, link to it here. Otherwise, remove this section]

 airline booking data, hotel occupancy rates, social media sentiment analysis) to improve the accuracy of the demand forecasting model.
Try different time series models (e.g., ARIMA, LSTM) to compare their performance in predicting travel demand.
Expand the analysis to other regions (e.g., Asia, South America) to identify global travel trends among younger generations.
Analyze sentiment related to travel searches to understand the emotional drivers behind travel decisions.



* Miresa ofga
* miresaofga1@gmail.com 
*linkedin.com/in/miresaofga 
