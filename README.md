# Analysis of fundraising goals of plays



## Overview
The purpose of this study is to perform data analysis on the dataset to find relationships between play launch data and campaign outcomes.   By doing detailed analysis on the different features such as goal, pledged, country, etc, we are able to find patterns in the data that shows a strong correlation between launch date and campaign success. 
## Analysis and Challenges
#### Analysis
In the study, I performed two analyses on the dataset.  
First is Theater Outcomes By Launch Date.  In this analysis, I grouped plays based on different launch date by month.  For each month, I collected campaign outcomes.  The result is present in figure 1.
![Figure 1](https://github.com/violetqq0221/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)
 
Second analysis is Outcomes Based on Goals. In this analysis, analyze the successful, fail and cancel by goal amount.  Plot each percentage rate based on different goal amount. 
![Figure 2](https://github.com/violetqq0221/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)
Link to the Excel sheet is [here](https://github.com/violetqq0221/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx).
#### Challenge
The most challenging part of the assignment for me is find meaning patterns in the data.  Because the dataset has mean different features, it can be not very straight forward to see patterns in the data.  Therefore, by using the data analysis techniques in the previous sections of the assignment, I am then able to draw meaningful conclusion from the data.
## Results
I was able to obtain the following findings.
Theater Outcomes by Launch Date
Over the period of time between May, 2009 to March 2017, the overall success rate is 61.3% (839/1369=61.3%) and also observe through the plot, the month of May is most successful month compared with other months. 
In the first quarter (Jan-Mar) and also during the holiday season (Nov and Dec), the campaign outcome failure rates are lower than other months.  Overall, the cancellation rate is 2.7% (=37/1369=2.7%).  It is not clear intuitively why this is the case.  

Outcomes Based on Goals
Based on the goal, the goal less than 1000 dollars is the most successful. The goal between 45000 to 49999 is likely to fail, no successful.  No cancel

As mentioned previously, it is sometimes not intuitively clear why the month of May has the best campaign success rate.  Also, the monthly data for failure rate is not clear, and we cannot draw any strong conclusion from the failure data.
In addition, we can perform additional analysis of fundraise goals in different countries.  We can present the data in tables for different countries or continents.  This can give us insight into how different regions of the world compare with the US, or how people’s behaviors are different in different regions.  We can further create box plots to compare the distribution of campaign goals and the pledge (standard Deviation, upper Quartile, Lower Quartile and IQR).
