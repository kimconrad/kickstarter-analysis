# Kickstarting with Excel

## Overview of Project

### Purpose

Analysis of Kickstarter Data to inform client decisions for success with her upcoming Kickstarter campaign.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Created PivotTable and Chart to summarize and visually show how quantity of successful campaigns related to when they were launched, specifically for Theater campaigns. Utilized Category, Date Created, and Outcomes as data points for analysis. Filtered for Theater parent category.

### Analysis of Outcomes Based on Goals

Created PivotTable and Chart to summarize and visually show how the success rate related to the goal amount of the campaign. Utilized COUNTIFS() function to summarize Outcome based on Goal amount and SUM() function to determine total projects for each Goal amount bracket. 

### Challenges and Difficulties Encountered

Minor difficulty with syntax of COUNTIFS() function. Referred to explainer video in module content and internet resources on Excel functions to correct error. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

1. The most popular time of year to launch a Theater campaign is early-mid summer: May, June, and July showed the highest quantity of launches). 
2. This is also the time of year with the highest quantity of success. The quantity of Failed or Canceled campaigns stayed relatively constant throughout the year with minor fluctuations, but the quantity of Successful campaigns in May was double that of March. The winter (especially Nov and Dec) has the lowest rates of success. 

- What can you conclude about the Outcomes based on Goals?

Campaigns are most likely to Succeed (and least likely to Fail or Cancel) if they have a Goal of less than $5000. Between $5000-40000 the rate of success stays fairly constant, and above $40000 a campaign is more likely to fail than it is to succeed. 

- What are some limitations of this dataset?

We do not have detailed information on what kind of marketing / publicity / communication was created for each of these campaigns. These actions could have a considerable impact on the success of a campaign in addition to the data points we have in this dataset. 
We also don't have data on individual contribution amounts, only the average amount for a campaign which limits further insights.

- What are some other possible tables and/or graphs that we could create?

We could use the Staff Pick and Spotlight data in a PivotTable to gain some insight into the effect of this marketing/communication on a campaign's success. 
We could also look at the Backers Count and Average Donation in connection with the Goal amount to gain insight into appropriate target audiences for future campaigns.
