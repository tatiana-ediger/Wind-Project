# Wind-Project
Analyzing the power generated from wind turbines given the time of day and environmental factors.

In our Fall 2019 Foundations of Data Science class, for our final project we wanted to focus on sustainability, and in particular green energy sources. Often times wind turbines are criticized and are called ineffective because they cannot convert wind into electricity at 100%, but because we recognized their potential, we wanted to take a look at the actual amount of power a wind turbine could generate to reduce criticism. We wanted to educate individuals in how effective their power generation could be.

For this project our goal was to gather weather data from a certain area, and determine the power that would be generated for a type of wind turbine from a variety of factors. We scraped data from NOAA on temperature, air pressure, wind speed, wind direction, and time of day. We then adjusted our data so that it was in terms of the correct units and used the different factors to calculate the Power Generated in watts. We looked specifically at whether the time of day (early morning, mid morning, afternoon or night) affected the amount of power generated, and the results of our ANOVA test provided evidence supporting a relationship between the two. We then used a predictive supervised regression model to predict the amount of power generated based on our features. Using feature selection, we ended up using only wind direction, wind speed and air pressure to make these predictions, and found that our training and testing data produced similar results, and when evaluating our models, we found that linear regression, Ridge, and Lasso algorithms revealed the best performance and are the ones that should be used for our predictive model.

The final write-up is in the file: DS3000_FP4_Section01_Group01.ipynb

The statistical testing scripts are in the file: Wind Project ANOVA.ipynb

The raw dataset is in the file: weather_data.csv

The transformed dataset is in the file: Transformed_csv.csv

The webscraping script is in the file: Web Scraping for Wind Project.ipynb

The visualization scripts are in the file: Wind Project Visualizations.ipynb And all of the actual visualizations are in the files labeled Wind Project Graphs.
