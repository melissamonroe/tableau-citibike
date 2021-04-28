# Tableau Homework - Citi Bike Analytics

Link to Tableau Public [Citi Bike Dashboard (Jersey City 2016-2017)]( https://public.tableau.com/profile/melissa.monroe#!/vizhome/citibike_16192476040720/DashboardSummary) 

## Background

![Citi-Bikes](images/citibike.jpg)

Congratulations on your new job! As the new lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) Program, you are now responsible for overseeing the largest bike sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so your first task on the job is to build a set of data reports to provide the answers.

## Task

**Data found in the Citi Bike Trip History Logs was aggregated to find unexpected phenomena. (Jersey City Data in 2016 and 2017)** 

Analyzation of Trip History logs revealed: 

- Most popular start and end station in dataset: Grove St PATH

- Bike IDs 24519 and 24711 had outlier trip duration (189 days and 55 days) Most likely these trip durations were recording trips while not in use. Possible explanations: lost stolen bikes while the trip is not ended.

- Weekends observed longer duration trips, while weekdays had more trips Weekends average trip duration: around 12 minutes. Weekdays total trips between ~75,000 to ~85,000 vs ~50,000 on Saturdays and Sundays.

- Peak usage (trip count) occurs at 8:00 AM (first peak) and 6:00 PM (second peak) on weekdays. Peak usage likely due to work related rush hour times, commute to and from work.

- Majority of riders are male. Majority of all riders age groups are late twenties and early thirties

- Most common rider age 31. Marketing demographic of users in this date range, male working professional in early 30s. Possible opportunities for increasing user base: marketing to females in the same age group.

- Across all ages, most trips are under a mile. A few high averages for rides in uncommon age groups. Approximate trip distance calculated (as the crow flies between start latitude/longitude and end latitude/longitude).

- Majority of users are subscriber user type. Peak months for rider usage (August & September 2016, August & October 2017). Lowest recorded trips during January 2016 (7,177).

- Ending Station Grove St PATH recorded more ending trips (~61K starting trips, ~80K ending trips), more often users were traveling from other starting stations to Grove St PATH. 

- On the ending station map, there are many stations that have only one recorded trip starting in Jersey City and ending in Manhattan, suggesting a flow of unilateral bike movement from Jersey City to Manhattan.

* How many trips have been recorded total during the chosen period? 502,638 (count based on cleaned data).
