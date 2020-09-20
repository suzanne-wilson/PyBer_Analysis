# PyBer_Analysis
## Delivering Results
# 
#### The purpose of this project is to analyze all the rideshare data from January to early May of 2019 and create a compelling visualization for the PyBer CEO.  We used the pandas Python library to prepare the data for analysis, and the matplotlib Python library to create the visualization. A summary dataframe, which presented several key measure summaries by city type was created.  To prepare for plotting the data, total fares per week by city type was calculated.  We found that total fares were consistently highest in urban cities, followed by suburban cities, and the lowest total weekly fares were found in rural cities (see Figure 1).

![PyberChallenge.png](/analysis/PyberChallenge.png)
---------
Figure 1. 

#### Summarizing the fare data to the appropriate level of analysis was challenging.  Using the resampling method on the data allowed for a lot of control over what the data summary looked like.  Working with the date index was also challenging.  Learning some of the pandas date functions as well as pandas Grouper allowed for precise preparation of the data.

#### Differences observed in weekly fares by city type may be driven by disparities that could be addressed by PyBer. There are two additional analyses I would recommend that may give a deeper understanding of the factors contributing to the differences observed in this analysis:
#### 1) Compare changes in the average fare per ride throughout the day in each of the city types.  Accomplish this by resampling by hour of the day and plotting average fare (y) by hour of the day (x)for each city type.  A spike in average fare could indicate demand is exceeding the supply of drivers.  This analysis could be done using the same dataset used for this analysis.

#### 2) Identify recurring events that could drive up demand for drivers.  Get data from area airports, entertainment venues, and large employers, and evaluate the average fare per ride in the hour before the event and the hour after the event.   

