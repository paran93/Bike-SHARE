BikeShare-DataAnalysis
-------------------------
With the use of Python, we explore data related to bike share systems for three major cities in the United States: Chicago, New York City, and Washington.
Hence answering interesting questions about it by computing descriptive statistics.
A script that takes in raw input to create an interactive experience in the terminal to present these statistics.
----------------------------------------------------

Bike Share Data
-------------------------
Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world.
Bicycle-sharing systems allow users to rent bicycles on a very short-term basis for a price.
This allows people to borrow a bike from point A and return it at point B, though they can also return it to the same location if they'd like to just go for a ride.
Regardless, each bike can serve several users per day.

Thanks to the rise in information technologies, it is easy for a user of the system to access a dock within the system to unlock or return bicycles.
These technologies also provide a wealth of data that can be used to explore how these bike-sharing systems are used.

In this project, we used data provided by Motivate, a bike share system provider for many major cities in the United States, to uncover bike share usage patterns.
We will compare the system usage between three large cities: Chicago, New York City, and Washington, DC.
----------------------------------------------------

The Datasets
-------------------------
All three of the data files contain the same core six (6) columns:
1. Start Time (e.g., 2017-01-01 00:07:57)
2. End Time (e.g., 2017-01-01 00:20:53)
3. Trip Duration (in seconds - e.g., 776)
4. Start Station (e.g., Broadway & Barry Ave)
5. End Station (e.g., Sedgwick St & North Ave)
6. User Type (Subscriber or Customer)

The Chicago and New York City files also have the following two columns:
1. Gender
2. Birth Year
----------------------------------------------------

Statistics Computed
-------------------------
We will learn about bike share use in Chicago, New York City, and Washington by computing a variety of descriptive statistics.
In this project, I'll write a script to provide the following information:

#1 Popular times of travel (i.e., occurs most often in the start time)
- most common month
- most common day of week
- most common hour of day

#2 Popular stations and trip
- most common start station
- most common end station
- most common trip from start to end (i.e., most frequent combination of start station and end station)

#3 Trip duration
- total travel time
- average travel time

#4 User info
- counts of each user type
- counts of each gender (only available for NYC and Chicago)
- earliest, most recent, most common year of birth (only available for NYC and Chicago)
