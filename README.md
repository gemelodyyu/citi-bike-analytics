# Citi Bike Analytics


## Background


As the new lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) Program, you are now responsible for overseeing the largest bike sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.


Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.


However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so your first task on the job is to build a set of data reports to provide the answers.


## Report 


[Link to my Tableau Public workbook](https://public.tableau.com/profile/ge.melody.yu#!/vizhome/CitiBikeAnalytics2020_16076277704260/CitiBikeAnalytics)


**Question 1**: How did the pandemic in 2020 affect the useage of the bikes? 


The year of 2020 has been really tough. The pandemic is changing many aspects of our life, including the way people commute. In this page you could see the change of average tripduration for each start station, the average tripduration for top 20 start stations, and numbers of customer verse subscriber from January (when the pandemic haven't started yet) to July (when the New York have made through the first wave). 


<img width="1226" alt="Screen Shot 2020-12-14 at 00 30 33" src="https://user-images.githubusercontent.com/55970064/102047901-bcb6eb00-3da3-11eb-8a95-db59db427cf5.png">

<img width="1226" alt="Screen Shot 2020-12-14 at 00 30 46" src="https://user-images.githubusercontent.com/55970064/102047920-c2accc00-3da3-11eb-883b-e690274bc610.png">

<img width="1226" alt="Screen Shot 2020-12-14 at 00 31 00" src="https://user-images.githubusercontent.com/55970064/102047936-c9d3da00-3da3-11eb-9bd3-ded31436e620.png">

<img width="1225" alt="Screen Shot 2020-12-14 at 00 31 18" src="https://user-images.githubusercontent.com/55970064/102047958-cfc9bb00-3da3-11eb-9df2-8ce643fcd2e8.png">


* In January, before the pandemic hit New York, the useage of Citi Bike was pretty evenly distributed acorss each Zip code area. 

* But in March, when the pandemic first started, the use of Citi Bike increased rapidly (probably due to the limitation of useing other public transportation like subway or bus), especially the Fairmount Ave station. 

* Comparing with January, there were much more 24-hour pass or 3-day pass users, and less annual members. 

* In May and July, with the situation of pandemic became more stabilized, other stations also had more useage comparing with January, but the useage was evanly distributed again. The number of 24-hour pass or 3-day pass users and annual members also became stable. 


**Question 2**: Which bikes (by ID) are most likely due for repair or inspection during January to July 2020?


* Bikes need inspection and maintance from time to time. This page highlighted the bike IDs that we believe due inspection based on the totle trip duration (over 1,500,000 seconds) or the average trip duration each month (over 50,000 seconds)

