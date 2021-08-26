# Kickstarting Analysis based on Campaingn Launch Date and Campaign Goals for Theaters in the USA

## Overview of Project

## Purpose:  
Analyze the given dataset on previous fundraising campaigns to identify factors that contributed to the success and failure of these campaigns.  Specifically, how did launch dates and funding goals affect the outcome of these campigns?  How did duration and/or the time of year affect the outcome.

 ## Analysis and Challenges:

### Analysis of Outcomes Based on Launch Date
- Extract the year our of the Date Created Conversionc column.

- Created a pivot table from Kickstarter worksheet

- I also extracted the month out of the Date Created Conversion column to break down my graph by month.  I was not sure how else to get the results expected based on the image of the graph. I used the MONTH function on the Date  Created Conversion and then added pne more cilumn to the Kickstarter Worksheet then used the TEXT function to convert the number to text.
### Analysis of Outcomes Based on Goals
- I used the COUNTIFS() funtion to populate the "Number Successful", "Number Failed", and "Number Canceled" columns from the Kickstarter Worksheet.

- Created pivot table based on 12 rows of pledged amoutn ranges.

- COUNTIFS() functioin Syntax was challenging as it is a long Syntax but once I got hte first couple of functions right, I was able to copy and paste into other cells.

- Even though my numbers are correct, my graph does not look the same as the one provided in the Module.
### Challenges and Difficulties Encountered
- I also extracted the month out of the Date Created Conversion column to break down my graph by month.  I was not sure how else to get the results expected based on the image of the graph. I used the MONTH function on the Date  Created Conversion and then added pne more cilumn to the Kickstarter Worksheet then used the TEXT function to convert the number to text.

- COUNTIFS() functioin Syntax was challenging as it is a long Syntax but once I got hte first couple of functions right, I was able to copy and paste into other cells.

- Even though my numbers are correct, my graph does not look the same as the one provided in the Module.


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  -People feel more generous in the month of May
  
  -People don't have exendible money during the Holidays

- What can you conclude about the Outcomes based on Goals?
 
  -Percentage of projects thayt fail steadily increase with the amount peldged

  -The most achielvable goal is the range of 1000-49999

- What are some limitations of this dataset?

  -This is a small dataset
  
  -This dataset covers a large range of countries and categories


- What are some other possible tables and/or graphs that we could create?
