# bikesharing
tableau

# NYC Citibike Analysis

# Overview of the statistical analysis:

The purpose of the current analysis is to prepare visualizations that give potential investors a look into the highly-successful NYC Citibike bike-sharing program, so that they can see for themselves that a bike-sharing program in Des Moines is a solid business proposal. Among others, we have prepared visualizations that,

1) Show the length of time that bikes are checked out for all riders and genders,

2) Show the number of bike trips for all riders and genders for each hour of each day of the week

3) Show the number of bike trips for each type of user and gender for each day of the week.

# Resources:

Source Files: 201908-citibike-tripdata.csv, 201908-citibike-revised_tripdata.csv

Software: Tableau, Python 3.7.6, Jupyter NB, Pandas Library

# Results:

1. Looking at visualizations for 'Checkout Times for Users' and 'Checkout Times by Gender', we see that most rides are for 20 minutes or less, and that the vast majority of rides are less than one hour. We also see that this pattern is the same regardless of gender.

![Checkout times for users](https://user-images.githubusercontent.com/96400887/180027197-bf48a960-235f-4254-a4a0-d1085685a9d3.png)

2. Total numbers of uses is greater among "MALE" riders,other pattern of the graph looks same as previous (regardless of gender).

![Checkout times by gender](https://user-images.githubusercontent.com/96400887/180030795-23fc5f5d-3ff6-4439-806e-76943c632fb9.png)

3. The heatmap of 'Trips by Weekday per Hour' shows a clear pattern of bicycle useage 1) during the morning weekday commute (7-9 a.m.), 2) during the evening weekday commute (4-7 p.m.) except on Wednesday evenings, and 3) all day long on weekends.

![bike share during weekday](https://user-images.githubusercontent.com/96400887/180031521-f74fb062-8309-46f8-81dc-314b5386c925.png)

4. Although useage is significantly higher among Males, the pattern of hours where bikes are nost-used is the same regardless of gender.

![bike sharing by gender](https://user-images.githubusercontent.com/96400887/180031733-8917d2c8-c267-48d0-b339-860b097a8ee4.png)

5. The Customers check bikes more often during weekends whereas Subcribers checkout bikes during Weekdays.

   Amongst Subscribers the Most busiest day is Thursday whereas the least busiest day is Sunday.
   
   ![usertrip by gender by weekday](https://user-images.githubusercontent.com/96400887/180031970-8d3d9404-7c6f-4527-bd16-4fe36eaff275.png)
 
 6. Comparing visualizations for the 'Top Starting Locations' and 'Top Ending Locations', we can see that the most active starting locations are also among the most active ending locations. This is important, because we need to know whether there might be an excess or shortage of bikes at particularly stations over time.
 
 ![Top starting location(with station name)](https://user-images.githubusercontent.com/96400887/180032698-92b53dce-b6fe-4e0f-8f8a-81b2537150b2.png)
 
 ![Top Laction(with station name)](https://user-images.githubusercontent.com/96400887/180032733-c116a490-e1ec-4c64-b913-ff88e3e9d8bc.png)
 
 
 # Summary:
 
 The results of this analysis have given insight into the utilization of bicycles in the NYC Citibike bike-sharing program. 
 
 We've seen the patterns of useage by time and by gender. Utilization rates can now be predicted based on time of day and location. 
 Weekday useage is heavily concentrated around the morning and afternoon commute. Weekend useage is more evenly spread through the day. 
 
 We would recommend further analysis for a few points. Firstly, while we've seen that the vast majority of trips are 30 min or less, we should perform further analysis to compare weekend trip durations to weekday trip durations. 
 
 We should also look further into the patterns of useage for the bicycles that see the heaviest use, perhaps preparing maps showing all of the starting/ending routes/locations for the heaviest use bikes. We should also prepare a visualization to determine if there are specific locations that are completely unused.
 
 


 
 
   

   
   









