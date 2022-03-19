# CitiBike Trip Analysis
Module 14 challenge prepared by Hannah Wikum - March 2022
___
## Resources
Data Source: 201908-citibike-tripdata.csv (August 2019 CitiBike trips from https://s3.amazonaws.com/tripdata/index.html)

Software: Tableau, Jupyter Notebook, Python with Pandas
___
## Overview
### Background
This analysis was completed to gather data about CitiBike usage in New York City. CitiBikes were first introduced in New York City in 2013 and are an affordable and eco-friendly transportation option for commuters and tourists alike. Users can check-out a bike at any of the stations and return it to another station when they are done using it. Riders have the option to pay for subscriptions to the service or purchase single rides or day passes. Bikes can be used at any time of day, 365 days of the year.

### Purpose of the Analysis
The purpose of this analysis was to analyze information on CitiBike usage in New York City to understand the potential for a similar bike-sharing service in Des Moines, Iowa. I used Tableau to create various visualizations of the data on information such as peak hours, total number of rides, breakdown of users by type (customer, subscriber) or gender (unknown, male, female), trip duration, bike utilization/repairs, and more. I compiled a number of the visualizations in a story that highlights key findings in the data to inform replicating the service in Des Moines.
___
## Results
I compiled my visualizations in a Tableau story so a viewer can flip through the various information and change filters. You can view my story at the following link:

[link to story](https://public.tableau.com/app/profile/hannah.wikum/viz/CitiBikeRideAnalysis/ChallengeDashboard?publish=yes)

Here is a breakdown of the visualizations that I chose to include to tell the story of the data:

1) **August Peak Hours by Start Time**

![image](https://user-images.githubusercontent.com/93058069/159129789-b64fc3aa-f085-4fc9-8bd8-f4acd5e14735.png)

My first visual is a horizontal bar graph that shows peak times based on when users started their trips in August. The top two times fall between 5-6pm and 6-7pm. In the morning there is another peak between 8-9pm. The pattern of peak times makes me think that commuters are a large driver of trips.

2) **User Type**

![image](https://user-images.githubusercontent.com/93058069/159129952-e68f7c66-d794-4094-bfcc-70c9292abd9b.png)

To provide more clarity on who is using the CitiBikes, my second visualization is a pie chart that shows the breakout between customers and subscribers. Of the 2.3M trips taken on a CitiBike in August, 81% were from subscribers. The CitiBike website defines a subscriber as a user who is an annual member, while a customer purchases a shorter-term pass. It is a good sign for Des Moines that only 19% of users are customers because this likely represents tourists and I would expect Des Moines to have much fewer tourists to support the business than NYC.

3) **Trip Duration**

![image](https://user-images.githubusercontent.com/93058069/159130197-20913580-79de-483a-a07e-b767f7c8fdd1.png)

When looking at all users (both customers and subscribers, all genders, etc.), the data for trip duration is heavily skewed to the right. The most common usage time is only five minutes, as you can see with the peak on the graph. Just over 35k trips were only for one minute! It is clear that the bikes in New York City are typically being used for shorter trips.

4)**Trip Duration by Gender**

![image](https://user-images.githubusercontent.com/93058069/159130329-5661fcd7-7cad-4bd4-9844-bd8185d87895.png)

The fourth visualization shows similar information on trip duration as the third, but adds the ability to view or filter results by gender. There are a lot more male users, but the most common trip duration for both male and female is similar. The most common trip duration for male users was five minutes, compared to six minutes for female users. Users with unspecified gender saw a wider range of trip durations with the most common being 11 minutes.

5) **Trips by Weekday Hour**

![image](https://user-images.githubusercontent.com/93058069/159130471-23f784cc-fe78-4d70-89c2-6659a2914044.png)

This heat map shows the hour of trip start times compared to the day of the stop time. In the first visualization, we saw that the peak number of trips occurred in the evenings (between 5-7pm) and in the mornings (8-9am). This chart shows similar information and provides more proof that commuters are driving a large amount of the trips because the peak times I mentioned are only the peaks on weekdays (Monday-Friday). The peak amount of trips started between 12-1pm on Saturdays and late afternoon on Sundays.




