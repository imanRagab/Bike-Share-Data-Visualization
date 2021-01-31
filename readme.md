# Bike Sharing System Data Exploration

## by Iman Ragab


## Dataset

The data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The data consisted of 16 attributes of approximately 183,412 trips. The attributes included data about customers, locations and dates of the trips.


## Summary of Findings

* Age distribution showed a right skewed distribution which has some outliers greaters than 100 which are a large numbers for the age but I think they are natural data and no need to be cleaned.

* Gender distribution showed that males are the majority of the bike share users.

* User type distribution showed that the the majority of bike share users are subscribers.

* Day of week distribution showed that Saturday & Sunday are the lowest days in trips and this is reasonable as they are weekends and people don't get to work.

* Hour of day distribution showed a bimodal distribution with two peaks in the 8 & 17 o'clock which are usually the starting & ending hours of the working day.

* Trip duration has a long-tailed distribution and when plotted on a log-scale, it looks normal distribution with mean around 11 min and has outliers above 1000 min with max of 1409 min.

* Age & trip duration distribution shows more density in the large trip duration in the age region between 20 to 40 years & more density in low duration trips in the 20 to 30 years age region.

* Hour of day & trip duration distribution shows more density in the large trip duration in hour 8 & between 17 & 18 which indicates that most of large duration trip starts in 8 o'clock & also between 17 & 18 which are working day start & end hours.

* Day of week & trip duration distribution shows less density on Saturday & Monday which proves our observation before that weekend days have less trips than normal days. It also shows that days with less trip duration density are Friday & Sunday which are the day before weekend and the second & last day in the weekend maybe people tend to relax in those two days.

* Day of week & Hour of day distribution shows more density on Saturday & Monday between hour 10 & 15 hour which is reasonable as they are working hours in the working days also shows less density on same weekend days in hour 8 & hour 17 (start & end of work hours).

* Hour of day with age distribution shows more density between hour 8 - 9 & between hour 17 - 18 for age between 20 & 50 years.

* Day of week with age distribution shows more density in high age on Monday which maybe because old people go out with their family in the weekend.

* Hour of day with gender distribution don't show change in the shape for male & female as both shows bimodal distribution with two peaks at 8 & 17 hours.

* Day of week with gender distribution shows less density on weekend days for both males & females.

* Gender with age distribution shows more density around 30 years in males while having more density between 40 & 60 in females.

* Trip duration & day of week & gender visualization shows that other gender has the largest trip duration & women has more trip duration than men. Also on weekend days the trip duration decrease for all genders.

* Trip duration & hour of day & gender visualization shows that other gender has the largest trip duration in hour 2 & 3 AM, also we can see that men have significantly larger trip duration in early hours of the day than women while in the rest of the day they have converging trip durations.

* Trip duration & day of week & user type visualization shows that customers has larger trip durations than subscribers & they also make larger trips on weekends than work days.

* Trip duration & hour of day & user type visualization shows that customers has the largest trip durations on hours 2 & 3 AM.

From all relations we studied we can conclude some interesting insights:

* Women have larger trip than men.

* Customers have larger trips than subscribers & they ride for more time on holidays.

* People in general ride more on working days & mostly on the start, end of day.

## Key Insights for Presentation

On the presentation I showed that bimodal distribution for time of the day shows that the most popular hours of the day for rides are 8 AM and 5 PM. These time of the day correspnods to when people go to or coming from work.

While the bivariate distribution of time of the day & day of week show that on weekends, the number of rides starts gradually increasing around 8-9 AM and gradually decreasing around 5-6 PM .

Also discussed the relation between Hours of Day and Days of Week as the bivariate distribution of time of the day & day of week show that on weekends, the number of rides starts gradually increasing around 8-9 AM and gradually decreasing around 5-6 PM .


Finally, I visualized the relation between Trip duration, day of the week & gender & I explained my conclusion that other gender has the largest trip duration & women has more trip duration than men. Also on weekend days the trip duration decrease for all genders.