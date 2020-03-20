# Baywheels Rides Data findings

Data analysis of baywheels dataset @ https://www.lyft.com/bikes/bay-wheels/system-data

## Dataset Overview

FordGo bike data as the name suggests is a bike ride data. The data is pretty descriptive and easy to understand. This specific jupyter notebook here is dealing with bike sharing data from 2017 to 2019. The data collected here is informative sparing few missing values. The project here follows all the four steps of data analysis process where the data is gathered, cleaned (quality and tidyness), lastly analyzed and visualised. The dataset has below columns :

- Trip Duration (seconds)
- Start Time and Date
- End Time and Date
- Start Station ID
- Start Station Name
- Start Station Latitude
- Start Station Longitude
- End Station ID
- End Station Name
- End Station Latitude
- End Station Longitude
- Bike ID

I added few more columns to the above original dataset to make analysis easier such as extracting year, month, weekday from the start date.


## Summary of Findings

- Out of the 5M rides in the data set, nearly 4M are from rides less than 15minutes and 1M are between 15mins to 30mins duration.
- There are some considerable amount of rides that span up to 8h which makes sense because people might be using the bike for entire day (8 hours).
- The year wise breakdown shows that the baywheels is a booming business with consistent growth year after year. We can use this to predict a growth rate for 2020 which can be used to make any business expansion decisions.
- The `rental_access_method` is absent prior to 2019 and it seems that many users prefer app over the clipper card.
- Very less number of rides come from bike share for all program. Perhaps this program was not a hit or this could be lack of awareness amongst the users about the program. 
- Commute hours (around 8AM and then again at around 5PM) seems to be most common times of the day where baywheels sees the peak usage. This can be used to drive business decisions such as availability, promos etc..,
- Customers usually keep the bike for longer durations compared to the subscribers. This can be used to target marketing based on ride duration differently between subscribers and customers. The median for subscriber rides is around 10mins whereas the median for customer rides is around 15 minutes. 
- Customers and Subscribers peak during the commute hours on weekdays
- Customer rides increase during weekends and Subscriber rides decrease during weekends
- On the weekends, Customer rides spike during noon and the rides frequency is generally higher throughout the day.
- Irrespective of user type, there are very less rides during off hours (11 PM to 5 AM) generally.


## Key Insights for Presentation

In the exploration of baywheels dataset, I have made following conclusions:

- There are two types of users - Customers and Subscribers. These two user groups vary significantly in their usage behavior. Most usage usually happens around commute hours. And Customer usage peaks during weekends while subscriber usage peaks during weekdays (and especially during commute hours).
- Summer months usually have high usage compared to holiday season or winter months. But this was not highly consistent across years speaking to the true Bay area weather!
- Clipper card adaption is still very low as most riders prefer paying via App.
- Bay area all wheels program is quite recent and it would be interesting to see how the program grows.
