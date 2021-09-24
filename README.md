
# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this project is to vizualize funding results based on their lanch date and goal to help Louise see how her play "Fever" compares to other performances around the globe.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
One way to analyse this data is by looking at the month the performance launched it's funding to see if certain months are more successful than others.  The line chart below shows the results of funding goals by month over the last eight years.  

![Theatre_Outcomes_vs_Launch](https://user-images.githubusercontent.com/90879042/134605053-f047273c-45a8-4fcc-ac63-f1eba0309851.png)

As you can clearly see in the chart above, the months of May through August have had the highest number of successful launches with May having the most.  


### Analysis of Outcomes Based on Goals
Another way to analyze this data is to see how successful funding is based on the goal that is set.  For example, are higher goals as successful as lower goals.  To visualize this set a line chart is used with tiers of funding along the horizonal axis.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/90879042/134605084-3e88ad99-cc41-486c-bb86-ca6b14e547df.png)

As the chart above shows, the lower the goal amount the higher the success rate with a couple exceptions.  


### Challenges and Difficulties Encountered
One challenge that users may experience in the first analysis is related to the "grouping" of dates in the pivot table.  The first time I came accross this in the real world it took some googling to figure out how to get the date to show up grouped by month as opposed to specific dates.  

A challenge I encountered in the second analysis was that my total count of plays did not match the dataset.  The reason for this was my formulas initially were all setup as just greater than and less than without an equals to. I added this to my formulas and created a pivot chart to verify numbers were accurate. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	1. The best time to launch a Theatre is the beginning of summer-May as this is the month with the highest success rate.  
	2. December is the worst time to launch as only about 50% of events are successful.

- What can you conclude about the Outcomes based on Goals?
	1. Generally speaking the lower the goal amount the higher the success - $35K-45K being the exceptions.
	2. Under no circumstance should you set a goal in the $45K-50K range.  If anything raise the goal about $50K.

- What are some limitations of this dataset?
	1. An interesting comparison would be to look at the financial situation of the countries to see how much that impacts funding - thinking the recession the US experienced 10+ years ago. 
	2. Having the Average Donation is likely good enough, but it would be interesting to see more data on donations - were there outliers that significantly increased the average?

- What are some other possible tables and/or graphs that we could create?
	1. A chart that shows the outcomes overtime as a percentage - this could also be achieved by using a 100% stacked area chart as well.  For example, it appears that October is a successful month however, looking at the success rate it's actually one of the lowest months due to the high number of failures.
	2. A chart that breaks it out by year to see if the rates have trended up or down that could be skewing our monthly date.  For example, did May of 2010 have 100 successful launches skewing the data to make it look more favorable.  













-------------------------------------
# Below is all the module practice items

# An Analysis of Kickstarter Campaigns.
Performing analysis on Kickstarter data to uncover trends
---
##Parent Category Outcomes
![image](https://user-images.githubusercontent.com/90879042/133870674-60b3d921-1723-4822-bdb2-9775c24ad886.png)
---
##US Theatre Outcomes
![image](https://user-images.githubusercontent.com/90879042/133870710-0608c917-853a-409f-a949-a21b96cab9a6.png)
---
##Analysis of Goals compared to Pledges

![image](https://user-images.githubusercontent.com/90879042/133870796-feee3422-bf8e-482d-a3bb-6bf36313148f.png)
---
