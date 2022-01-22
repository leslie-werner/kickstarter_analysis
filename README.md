# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis is uncover trends using Kickstarter data. We want to know how campaigns did in relation to their launch date and their funding goals. We will be taking a closer look to see if the theater category either was successful, failed, or was canceled and the relation to the month it launched. Secondly, we will analyze the outcome of goals and the percentage of plays that either were either successful, failed, or were canceled within the play category based on goal set. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
When analyzing outcomes based on Launch Date, we can see that the overall rate of successful campaigns was a lot higher than failed and canceled. Taking a closer look, we can see that May had an all-time high of success while in December, the successful and failed campaigns had relatively similar outcomes. 
    
 ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/65638310/146682599-8e6ad6cc-d73d-4df6-8cbc-060d63a7ef9e.png)

### Analysis of Outcomes Based on Goals
When looking at the line chart, we can see that goal outcome and percent of success and failed campaigns start and end differently and that none of the plays were canceled. We can see that the success of plays being fully funded are high towards the beginning of the chart. As we progress beyond $15,000 a change starts to occur, and the failed campaigns are much higher than the successful campaigns. As the goal amount begins to increase, successful campaigns have a higher percentage rate than failed (seems towards the middle of the chart). At the end of the chart, the failed campaigns are a much higher rate than successful campaigns.    

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/65638310/146682730-0a5395a8-b277-4be0-8f21-2f728431f3b4.png)

### Challenges and Difficulties Encountered
A few challenges encountered in analyzing this data was trying to use the COUNTIFS() function to be able to set ranges of the goals. After doing more research, I was able to understand that the same criteria range had to be used in order to add multiple ranges. For example, I had to include column D twice to be able to accomplish two data set ranges.
Another difficulty that someone could encounter is not setting the correct filters for the data. This could cause having different data being analyzed.

## Results 

- What are two conclusions you can draw about the Outcomes based on Launch Date?
When we look at Theater Outcomes Based on Launch Date, we can see that overall successful campaigns are relatively higher than failed or canceled campaigns. We can conclude that during the month of May to August, you will have more success at meeting goals thus making it an ideal time to fund for campaigns during this time. We can also conclude that in the month of December you will have a harder time to meet goals and are almost equally as likely to fail versus succeed.   

- What can you conclude about the Outcomes based on Goals?
    When looking at the data, overall success was at a higher rate when the goal amount was lower and failed campaigns were higher towards the end of the chart. We can conclude that that too high goal amount has a higher tendency to fail. Thus, implicating that lower goal amounts are recommended in order to meet the goal set. 


- What are some limitations of this dataset? 
Some limitations of this dataset are analyzing the weather/season of the year in each country. By looking at the time of the year one can see if the temperature outside an influence in someone may have wanting to donate money for an indoor activity. Another limitation of this dataset is to see if holidays would also play a factor in each country. For example, do other countries celebrate Christmas and thus cause December to have a similar amount of success and failed campaign for Theater Outcomes Based on launch Date?

- What are some other possible tables and/or graphs that we could create?
It would be a good idea to make a table to see if Outcomes based on Launch Date per country. This would allow us to see if there is a correlation based on seasons of the year in specific countries and the success of theater campaigns being meet. We could ask if maybe in the summertime people are more willing to donate compared to wintertime. 
We could also make a graph based on category outcomes in relation to goals. For example, if animation will have overall higher success rates for goal to be meet compared to plays. By making a graph we can visualize which one will has a higher rate.
