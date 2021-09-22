# Kickstarting with Excel

## Overview of Project
The purpose of the analysis provided is to aid Louise in her efforts to produce a play called Fever.  Louise is curious about how other campaigns’ launch dates and funding goals relate to her own goals for Fever.

### Purpose

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The initial analysis performed was teasing out the data related to theater outcomes based on launch date.  There was a total of 1,369 campaigns with 61% of them being successful, 36% were failed and only 3% were canceled.
There were 839 successful campaigns with May and June being the peak months for success.  April and July were the next highest months for success.  It appears that campaigns with launch dates starting in mid to late spring through early to mid-summer will prove to be the most successful.  Of the successful campaigns, 14% of them were staff picks.
There were 493 failed campaigns related to theater that doesn’t seem to have any single month with an exceptionally high or low fail rate.  Starting in July, the failed campaigns were trending down though October did see a slight spike before November and December trailed down.  Of the failed campaigns, 98% of them were not staff picks.
There were only 37 campaigns that were canceled, and of those, January was the month with the highest number of cancellations at 7 and none of them were staff picks.

### Analysis of Outcomes Based on Goals
The final analysis performed was researching outcomes based on goals within the subcategory Plays.  There was a total of 1,042 projects with an average of 46% successful and 54% failed. (Note: there weren’t any canceled projects.)
Of the 693 successful projects, 387 saw success with a goal of $1,000 to $4,999.  This was the highest number of successful projects within a given range (up to $50,000) and accounts for 56% of all successful projects.  
Coincidentally, of the 349 failed projects, the highest (146 or 42%) failed within this same range of $1,000 to $4,999.  If Louise is to have a goal of $10,000, 39 were successful within the range $10,000 to $14,999 and 33 failed, 54% and 46%, respectively.  In looking at the next range down ($5,000 to $9,999), 93 (or 55%) were successful and 76 (or 45%) failed.

### Challenges and Difficulties Encountered
The outcomes based on goals portion of the analysis was trickier than the theater outcomes by launch date analysis.  This is due to the fact that I have limited history with using the =COUNTIFS() formula though it isn’t a difficult concept or task.  The biggest key to success for me was an attention to detail.  The table had 12 ranges and the formulas needed to pull in the correct range for the correct column of data while also filtering in only data for plays.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
In relation to the theater outcomes by launch data analysis, two conclusions were made.  More projects were successful than failed/canceled.  In addition to generally having a 61% chance of success, that number can increase if the project has a launch date beginning in May.  I think it also makes senses to put weight into the staff picks as 87% that were staff picks were successful overall.

- What can you conclude about the Outcomes based on Goals?
In relation to the outcomes based on goals analysis, one conclusion was made.  67% of projects were successful within the subcategory plays with a higher rate of success if Louise’s goal is set within the $1,000 to $4,999 range.

- What are some limitations of this dataset?
It should be noted that the data is several years old and goes back not quite ten years as well.  Prior to Louise moving forward, it may behoove her to obtain data from more recent years.  I’m also uncertain of the effect that currency conversion may have on the data.  If the country is where the goal is based and donations were foreign, that may have skewed the goal due to a favorable or unfavorable currency conversion.  

- What are some other possible tables and/or graphs that we could create?
Pulling in the difference between the goal vs pledged may be useful as well.  Simply because a project doesn’t meet it’s goal, doesn’t mean it’s a failure and Louise may still find that she’s willing to proceed with only 50% of funding being met.

