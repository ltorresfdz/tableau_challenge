# tableau_challenge
BOOT CAMP ITESM  -  TABLEAU HOMEWORK


# Citi Bike Analytics  

Purpose of this ITESM Boot Camp Data Analytics Tableau Assignment:  implement a dashboard or sophisticated reporting process for the New York Citi Bike Program.  

**Data information:**  
Data source: Citi Bike Data
Using python to scarp data web site to download the information and generate data frame, then convert to csv files.   Timespan used for analysis is 2019 and 2020.  

**Reporting Description:**  
In this link, please find the story proposed to be used in an annual Strategic Planning Sessions for the New York Citi Bike Program and presented to city officials looking to publicize and improve the city program:
https://public.tableau.com/profile/laura.ang.lica.torres.fern.ndez#!/vizhome/Tableau_Challenge_Citi_Bike_Analytics/Story1?publish=yes  

![alt text][story]

[story]: https://github.com/ltorresfdz/tableau_challenge/blob/main/Story%20pic.jpg "Tableau Challenge"

In the Story created there are 7 points, each one with different dashboard information:
1)	General Overview of Ridership 2019 vs. 2020:  Presents a dashboard with visualization or total trips made by month.
2)	Identify Peak Days and Peak Hours for Traffic Safety Measures: presents graphs comparing 2019 vs. 2020 total number of trips by day of the month. 
3)	Top & Bottom Stations: shows the 25 top & bottom stations where the trip starts and ends by type of user: customer 24-hour pass or 3-day pass user or Subscriber = Annual Member. On the 2020 graph, when clicking on specific station, it shows information on the average distance trip by bike. 
4)	Bike User Profile by Gender and Age shows bike trips by gender and age for 2020 data and by user type, customer, or subscriber. 
5)	Bike Data First part: total number of Bikes 2019 and 2020, and number of bikes grouped by total distance usage.
6)	Bike Data Second part: shows the info of each bike for year 2020: total distance, number of trips by bike, average duration trip by minutes. 
7)	City maps showing start and end stations, with tooltip info. 

**Insights:**  

1)	Impact of Covid19 Lockdown during 2020: there was a great decrease of trip from March 2020 to April 2020. 
2)	Despite the Covid19 epidemic, the trend is that from starting MAY till SEPTEMBER trips increase and starting in October total trips start decreasing. During winter Months -December, January, and February - Trips level tends to be the same. 
3)	Total number of trips 2019 vs 2020 slightly decreased.  Peak day of the month for number of trips is mid-month, around day 15th, by the end of the month total number of trips decreases.  Peak hours of bike trips are 8 am and 5pm; start & ending business hours. The period with the highest peak of bike trips is the leaving office hours’ time. These does not change during winter of summer months. 
4)	The largest average distance trip goes from 15-20 miles.  The smallest average distance trip is 2-4 miles. 
5)	In 2020 the proportion of Customer’s Bike Trips is higher than 2019.  More users are preferring paying for the 24 hrs. or 3-day pass, rather than having the annual subscription. Probably this is because of the effect of the pandemic, users did not renew the annual subscription. 
6)	TOP 25 start & end stations are almost the same, therefore it is very important that enough number of bikes are available during peak hours and have the enough area for bike parking in those stations.
7)	Bike Trips are mostly done by male users.
8)	It seems that when selling 3 day or 24 hrs. pass, the gender is not captured, since mostly are unknown.
9)	2020 data shows that most of the bike trips are done by customers of 51 years old, where most of them are only customers (24 hrs. - or 3-days pass).  Removing this peak, it seems that age users follows a normal distribution where most of the users are among 24-34 years old. 
10)	Birth Date information after 80 yrs.-old looks like it is false, since passing this age, the average number of trip duration is awkward, i.e..: trips of 205 minutes by an 86 yrs. old; there are customers of over 100 years with average duration in minutes of bike trips of 1,250 minutes.  

**Conclusions:**  

1.	Make a correction in the birth date capture process to avoid incorrect date of birth.
2.	Modify prices for annual subscription or offer additional benefits to increase annual subscribers that means a steady cash inflow.
3.	Define the advertising plan in each of top stations tailored to 24-34 yrs old users. 
4.	Negotiation acquisition program of new bikes or define bike maintenance programs for the 87 bikes that are used over 4,000 miles. 
5.	Define advertising plan on how canto attract more female users.
6.	Deep research on 51 yrs.-old users?
7.	Most of the bikes have among 1,000 to 2,000 miles usage. Define Maintenance and inspection to do it during end of the month.
