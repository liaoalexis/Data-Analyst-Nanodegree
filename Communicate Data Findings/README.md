# Project - Ford GoBike System Data Exploration
## by Xinyi Liao


## Dataset

The data consists of all the information regarding the rides taken in February, 2019, within the Ford GoBike System of the greater San Francisco Bay area. The data originally contains 16 attributes, including details such as duration, start and end times, station locations, user type, and demographic information of the trips. The dataset is stored as over 40 MB csv file, can be downloaded [Here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv), with more information about the data available [Here](https://www.kaggle.com/datasets/chirag02/ford-gobike-2019feb-tripdata).


## Summary of Findings

Throught the data exploration process, I used different visualization techniques to gain a deeper understanding of the relationships between variables. In user components, 90% of the users are subscribers, 75% are male, and age range is between 25 and 40. In terms of time duration of the trips, almost 99% of them are short and fast trips, despite of the outliers > 20 hrs. Majority of the trips are between 0.1 hr - 0.2 hr (6 mins - 12 mins). The trip counts reached its peak at 8 a.m. and 17 p.m. during the day, with business days (Mon-Fri) having more trips than weekends. The service is popular among Subscribers for work commute purpose. 

In the investigation of linear relationship between numeric variables, I found out start_hr and end_hr have strong positive correlation, but other numeric variables do not have any strong relationship with each other. Bivariate and multivariate exploration of trip duration, user type, and gender revealed that the difference in trip duration between customers and subscribers becomes more evident when analyzed across hours of day and different days of the week. Customers generally have longer trips regardless of the day, with the longest trips on weekends. Subscribers have shorter trips overall, but with a slight increase in trip duration on weekends. The trip duration patterns across genders are more pronounced when considering user type. Among customers, female users tend to have longer trips than males and other genders. However, among subscribers, male users have the shortest trip duration range, which is an interesting observation.


## Key Insights for Presentation

For the presentation, I focus on the user base, trip counts per hour/day, and trip duration. I start by introducing the
user types, followed by the pie chart in User Type distribution. Then, I will introduce the time segments, use two barplots because they are clear examples to show the useage pattern during the hours and days by two different user types. After that, I will follow a box plot about trip duration by user types. At last, I will show the point plot about average duration by day and user types, make sure it's clear to see the difference of average duration between weekdays and weekends.