# Kickstarting with Excel
## Table of contents
* [Overview of project](#overview-of-project)
* [Purpose](#purpose)
* [Analysis and challenges](#analysis-and-challenges)
* [Analysis of Outcomes Based on Launch Date](#analysis-of-outcomes-based-on-launch-date)
* [Analysis of Outcomes Based on Goals](#analysis-of-outcomes-based-on-goals)
* [Challenges and Difficulties Encountered](#challenges-and-difficulties-encountered)
* [Results](#results)

## Overview of Project
We performed data anlysis on roughly 4000 Kickstarter projects. Our goal was to find out what patterns lead to successful - and unsuccessful - crowdfunding projects for a client, Louise. These insights needed to be easy to understand so she could make informed decisions about how to configure her own Kickstarter project to be successful.

### Purpose
Louise needed to see information to help her plan her theater-based campaign, and undestand how similar successful campaigns were set up. She had ideas for budget (estimated cost of $12000), and she has some successful theater campaigns she'd like more information about. Since there are many ways you can set up a Kickstarter, we wanted to determine the effects of different choices for things such as:
* length of campaign
* goal amount
* month created
* category
* country

## Analysis and Challenges

First we took a look at the data that was provided from Kickstarter. We had to format information, split data into new columns, and add conditional formatting to help Louise interpret the information. We made sure the data was organized and sorted. We created visualizations that help show trends of the data and improve our ability to perform our analysis. We used statistics to allow us to view outliers and averages for our final report to Louise.

Specifically we had a few questions to answer such as: 
- Is a theater type of Kickstarter successful?
- What is the most successful length of a Kickstarter campaign like Louise's? 
- Is there a certain time of year when campaigns like this are most successful? 
- What is a successful goal amount for this type of Kickstarter?

![parent_category_outcomes](/resources/Parent_category_outcomes.png)

![subcategory_outcomes](/resources/Parent_category_outcomes.png)

We were able to see that theater Kickstarters, specifically plays, are a successful category of campaigns. We began to drill down into what types of choices made by the campaign creator would then positively affect the outcome of their theater campaign.

### Analysis of Outcomes Based on Launch Date
By visualizing the information of outcomes and launch dates over time, we can see that there are trends that change for when a theater campaign is successful. 

![outcomes_by_launch_date](/resources/Theater_outcomes_vs_launch.png)

#### Successful campaigns
* The most successful theater Kickstarters were launched in May. 
* After May, the success trends down until September. 
* There is a small increase in successful theater campaigns in October and November, then the successful campaigns drops sharply through December. 
#### Failed campaigns
* The failed theater campaigns appear more consistent throughout the calendar year, with small dips and spikes. 
* The top months for unsuccessful campaigns were December, then September and August.
* December had the highest number of failed Kickstarters for the theater category.

### Analysis of Outcomes Based on Goals
Looking at the information of outcomes by goal, we can visualize which successful play Kickstarters were funded successfully, which failed, and which were canceled based on the amount set as the campaign goal. 

![Outcomes_vs_Goals](/resources/Outcomes_vs_Goals.png)

#### Successful campaigns
* The percentage successful started high at 80% for goals less than 1000.
* The number of successful campaigns went down to around 20% when the goal amount went up to the range of 25000 to 29999. 
* The percent of successful theater Kickstarters went back up to nearly 70% successfully funded around a goal of 35000-39999, then dropped sharply to 0 at 45000 to 49999. 
* Goals greater than 50000 were at just under 20% successfully funded.
#### Failed campaigns
* The percentage of failed Kickstarter campaigns followed the inverse trends of the successful trends.
* For goals lower than 1000, failed kickstarters were at around 20% and then rose when the goal amount went up to the range of 25000 to 29999. 
* The percentage failed and percentage successful overlapped at three points, around 15000-19999; again at just before 35000-39999, and again before 45000-49999. 

### Challenges and Difficulties Encountered
#### Limitations of the dataset
- This dataset does not provide tertiary categories to inform us whether a "theater" Kickstarter campaign was to produce a play, or to build a theater. The type of campaign to produce a play is what we are most interested in; we'd have to read each blurb to exclude certain rows from our analysis.
- We cannot tell if a small amount of backers or even the person who originated the Kickstarter provided the majority of the funding for the campaign; we found the mean of the average donation but if one or two people donated most of the funding, then the actual amount donated by excluding those outliers would be much lower.
- We are unable to say whether backers were from the same country as the campaigns, or if they were in certain age brackets, income brackets, etc.

## Results

### Outcomes based on Launch Date
1. Based on these findings, Louise would be most likely to have a successful theater campaign if she launched it in May. 
1. Louise should not launch a theater campaign Kickstarter in December, followed by September and August.
### Outcomes based on Goals
1. From this information we'd recommend that Louise create her Kickstarter for a play with a goal no higher than 4000 for it to have the greatest chance (76%) of success. If she still estimates her costs to be at $12000, she may want to get additional funding using a separate method.
### Limitations of this dataset
The dataset was able to get to a lot of the questions we had, but it did not include categories beyond parent and subcategory. It also did not give us demographic information about backers, or a breakdown of pledge amounts by individual.
### Other possible tables and/or graphs
Our dataset included information on whether or not a campaign received a staff pick, which means it was promoted on Kickstarter in their newsletter and on their website as a compelling project for people who click on the Advanced Discover tool when sorting by "Magic". More analysis could be done to find out if that contributed to a campaign's success.

[View the Kickstarter Discover Magic page](https://www.kickstarter.com/discover/advanced)
