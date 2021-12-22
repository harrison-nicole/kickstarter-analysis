# Kickstarting with Excel

## Overview of Project

### Purpose
The goal of this analysis was to understand campaign outcomes based on launch date and funding goals in an effort to inform Louise's campaign for her play *Fever*.

## Analysis and Challenges
This analysis was completed by utilizing a pivot table and the COUNTIFS() function in excel. 

### Analysis of Outcomes Based on Launch Date
The first analysis, outcomes based on launch date, was designed to help Louise understand what launch date timeframes (by month of year) led to the most successful campaigns. Additionally, we were also to see which launch dates (by month of  year) led to more failed campaigns. 
![Outcomes Based on Launch Date](htps://github.com/harrison-nicole/kickstarter-analysis/blob/01e8cda4300d484f52ed74e8866118ce20202d9c/Challenge%20Resources/Theater_Outcomes_vs_Launch.png).

### Analysis of Outcomes Based on Goals
The second analysis, outcomes based on goals, was designed to help Louise understand what funding goals led to the most successful and/or failed campaigns. She can use this information to inform her funding goals for future campaigns.
![Outcomes Based on Goals}(path/to/Outcomes_vs_Goals.png).

### Challenges and Difficulties Encountered
The analysis for this project did not pose many challenges. That said, one key learning opportunity was to utilize the F4 key to ensure the COUNTIFS forumlas remained static. Without this step, the results for the outcomes based on goals analysis would not have been accurate with the formula moving.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The outcomes based on launch date analysis provided advantageous information for Louise. Two key findings are as follows: 
1) May, June and July saw the most number of successful campaigns. This might suggest Louise consider launching her campaign in one of those months. 
2) December saw the highest ratio of failed campaigns. This might suggest that Louise avoid launching a campaign in December. 

- What can you conclude about the Outcomes based on Goals?
The outcomes based on goals analysis provided helpful information for Louise. Most notably, the analysis demonstrates that campaigns with goals less than 9999 had the highest percentage of success rate. As campaigns increase in goal, the rate of failure increases (except between 35000 to 45000). 

- What are some limitations of this dataset?
One limitation of this dataset is the sample size. There are 1047 plays in this dataset and while that provides a good foundation for analysis, it's important to note that there were very few campaigns with gosls greater than 25000. For example, there was only one play with a goal between 45000 and 49999, which failed and resulted in a 100% fail rate for that goal category.

- What are some other possible tables and/or graphs that we could create?
Other possible tables and/or graphs to consider include: 
1) outcomes based on country
2) outcomes based on country and goal (or launch date)
3) outcomes based on number of donations and average donations
