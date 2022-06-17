# Kickstarter-analysis
Performing Analysis on Kickstarter data to uncover trends
## Overview of Project
This weeks challenge helps us build upon our skills learned in the Excel module. In a short amount of time, Louise's play fever came close to reaching its fundraising goal. The purpose of this analysis was to find out how different campaigns fared in relation to their launch dates and their funding goals.
## Analysis and Challenges
The analysis had two tasks. First, a pivot table was created to show the theater outcomes by launch date. To make sure it was the right data, we filtered for the theater criteria in parent category. Next, we showed the number of "successful", "failed", and "canceled" projects by month on line chart, as shown below.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/107658895/174225211-7f2fc393-2554-4b2a-b95a-8c06037ced93.png)

The second task was to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount. This was done by honing our excel skill of the 'countif()' function. For our purpose, this function counted the outcomes for the different goal ranges. This result was populated in a table and specifically filtered for the subcategory 'plays' in each goal range by "Number Successful", "Number Failed" and "Number Canceled". These criterias' percentage of successful, failed, and canceled projects were calculated for each goal range. A line chart was generated to visualize the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis, as shown below.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/107658895/174226764-5bfb1740-de0d-49f5-8afe-95b9ca2a5642.png)

The most difficult thing for these tasks was making sure that you were filtering for what was being asked. For me, I had trouble, initially, filtering the correct data from the required 'subcategories' when doing the countif function. I overcame this following the tutorials in the module 1 to get the correct Outcomes based on Goal graphs.

## Results
Based on the results of the Theatre Outcomes by Launch Date, I can say that people really like attending plays come summer time. On average, I believe this is around the time of the year when people can take their vacations and do more leisurely activity. There also seemed to be a spike in failed outcomes around September-November which coincided when there were no canceled theater outcomes. For now, the best chances to have successful theater outcome is on February to September.

It seems that your play's outcome has a better chance of being successful than failing if its goal range is less than 20,000 or from 35,000 to 45000.

The limitations of this dataset is that it only provides a narrow time window. This data isn't as representative as if it had it for a wider time range. It also didn't consider every country. I'd like to see how these charts looked for the top 3 countries that spent the most money. I'd also like to see which countries have donated the most money and for which genre.
