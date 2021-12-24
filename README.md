# Kickstarting with Excel

## 1. Overview of Project
All in all, Louise wants to find out the relationship, in her subcategory plays, between lanuch dates and funding goals. With the analysis done in deliverable 1, Louise can plan around the months that have a high rate of failures and turn it around. For deliverable 2, Louise can easily analyze who had the lowest and highest percentage rate based on goal range.

## 2. Analysis and Challenges
 The analysis was done by using different tables that allows readers to easily view and analyze.

### Analysis of Outcomes Based on Launch Date
[Pivot Table for Outcomes Based on Launch Dates](resources/PivotTable_Oucomes_Launch_Date.png)
<br>
[Line Graph for Outcomes Based on Launch Dates](resources/Theater_Outcomes_vs_Launch_1.png)

A pivot table and a line graph were used to view the outcomes based on launch date. The pivot table will help Louise spot which months had a higher number of success vs failers or canceled (if available) outcomes. If she wanted to more research based on years, Louise could simply filter by a specific year. The line graphs help Louise visualize which months might need more help based on their failure or canceled rate.


### Analysis of Outcomes Based on Goals
[Line Graph for Outcomes Based on Launch Dates](resources/Outcomes_vs_Goals.png)

The analysis on outcomes based on goals was interesting to see because there were no cancelations involved for the subcategory plays. Seeing this makes me want to dig deeper and see when did each of these successful or failure outcomes launch ? Was it during a specific month or different months? Aside from questions arising, the line graph that was created helps us also see that there were more successful outcomes than failed throughout the different goal ranges.

### Challenges and Difficulties Encountered
While performing my analysis, I saw myself trying to figure out the 'what' behind some of the results. For example, in the 'Outcome based on Goals' tab shows that there were 0 number of cancled outcomes, but what does 0 canceled outcomes mean?  

I also had a challenge using the countifs function for the same range in the same column. I quickly googled and this site showed up and helped me out with the following formula too:

-[Website for countifs](https://www.ablebits.com/office-addins-blog/2014/07/10/excel-countifs-multiple-criteria/)

-Formula I did not know could be used: 
			"(...Kickstarter!$D:$D,">=10000",Kickstarter!$D:$D,"<=14999...)"

## 3. Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Out of all years, the month of May is where Louise had the highest succesful outcome rate. We can also conclude that overall, the outcome of successful is higher than failed for all months except December.

- What can you conclude about the Outcomes based on Goals?
What can be concluded about the outcomes based on goals is that for each goal, the percentage of successful and failed are always opposite, with the exception of a goal (15000-19999), where they meet half way.

- What are some limitations of this dataset?
A limitation that I encountered with the dataset was converting the deadline and launch dates to a readable format.

- What are some other possible tables and/or graphs that we could create?
Another table that can be introduced is the box and whiskers. This table can help Louise or anyone viewing the graph the outliers based on launch date or goals. 
