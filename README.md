
# PyBer_Analysis
# PYBER CHALLENGE ANALYSIS 
# BY MONICA M. HOLMES  
# March 26, 2021


##**1.	Overview of the analysis:**##
•	The purpose of the new analysis is to create visualizations of rideshare data for PyBer to help improve access to ride-sharing services and determine affordability for underserved neighborhoods. 
•	To do this I will create a summary DataFrame of the ride-sharing data by city type. Specifically, I got the total number of rides, total number of drivers, and the total fares for each city. Next, I will calculate the average fare per ride and average fare per driver for each city type. After that, I will add the data to a new DataFrame, then format the columns. Lastly, I will create a multiple-line graph to show the total fares for each week by city type.
##**2.	Results:**##
o	The Ride-sharing data includes total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type, each are described as follows:

o	Total rides are a Series of data where the index is the type of city, and the column for the Series is the number of the rides for the type of city.
o	Total drivers are a Series of data where the index is the type of city and the column for the Series is the sum of drivers for the type of city.
o	Total fares are a Series of data where the index is the type of city and the column for the Series is the sum of fares for the type of city.
o	The average fare per ride was calculated by taking the total amount of fares divided by the total amount of rides. 
o	The average fare per driver was calculated by taking the total amount of fares divided by the total amount of drivers.
o	The total fare by city type is a summarized by week.
o	Below is a screenshot of the PyBer Summary which shows that although the Rural cities had 13 times fewer total rides than Urban cities, on average, the Average Fare per Driver cost is $38.92 higher than Urban cities. However, because there are less drivers and rides in Rural cities, the Total Fares are about $35k less than Urban cities.

![image](https://user-images.githubusercontent.com/78371845/123722809-15893500-d857-11eb-86b2-3a657f6c1827.png)


o	The screenshot of total fares by week shows the first 10 rows of data, which highlights the fares earned by week for each city type and shows Urban city types made the most per week. There is also a correlation the week of February 24, 2019, which was the highest earning week for each city. There is not a correlation in the lowest earning week amongst city types.

![image](https://user-images.githubusercontent.com/78371845/123722853-29349b80-d857-11eb-86af-74543ea5d1dd.png)



o	A snapshot of the sum of fares shows our data has 2,375 rows of data spanning the first four months of 2019 and are time and date stamped. 

![image](https://user-images.githubusercontent.com/78371845/123722882-3782b780-d857-11eb-863c-2b8448989866.png)


o	A look at the multiple-line chart created to summarize the results shows, the February 24, 2019 corresponding increase, then a corresponding decrease in fares the next week in March 2019, which may be related to people taking transportation for March Madness. There was also a small increase in fares for all three types, the first week of April 2019. These three weeks were the only correlations. 


![image](https://user-images.githubusercontent.com/78371845/123722912-45383d00-d857-11eb-81c4-471197128113.png)



##**3.	Summary:**##
o	In summary, it is not surprising that rural type cities have the lowest ride-sharing revenue, as most people in rural cities, have a vehicle since public transportation is limited. It also is not surprising that the average cost for rides-sharing is more expensive for Rural cities, than Urban, as the distance per ride is probably farther. Likewise, the disparities are not surprising that Urban type cities have the highest amount of revenue because there are more people traveling without vehicles and more drivers working ride-share. Suburban type cities, however, fall within the middle of the total’s fares by city type, as expected, since Suburban cities have a mix of population with and without vehicles and mass transportation is better than Rural but not as dynamic as Urban. Lastly, to help improve access to ride-sharing services and determine affordability for underserved neighborhoods, it is recommended to lower Rural city rates and increase advertisement for Rural drivers, which increases availability and revenue. It is also recommended to lower the fare cost per ride for Suburban cities, to draw in more riders. Lastly, capitalize from holidays and events across all city types by increasing advertising and driver availability. 


















