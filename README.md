# Kickstarting with Excel

## Overview of Project
 
### Purpose
Louise would like to compare how different campaigns fared in relation to their launch dates and funding goals. I will be performing analysis on Kickstarter data to uncover trends. Using the analysis on the Kickstarter data, two graphs were created to visualize the data. These graphs are on the outcomes based on goals and outcomes based on launch date.

Deliverable 1 shows knowledge of pivot tables and graphs to visualize campaign outcomes based on launch date. Deliverable 2 shows knowledge of new Excel formulas and functions to visualize the percentage of successful, failed, and canceled plays based on funding goal amount category.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I performed this analysis through the Kickstarter dataset provided by using pivot tables and graphing in Excel to visualize the campaign outcomes based on launch date. 

I created a column called "Years" to be able to filter by year on the data. I then created a pivot table with the Kickstarter data in a new sheet called "Outcomes Based on Launch Date" with filters for Parent Category and Years only showing successful, failed, and canceled projects. I grouped the row labels to only show months of the year. I filtered the data to only show theater info so that it could relate to Louise's problem. Using this filtered data, I created a chart called "Theater Outcomes Based on Launch Date" to visualize the information.

![](/resources/Theater_Outcomes_vs_Launch.png)

Looking at the line chart above, we can see that the most theater projects were successful in May and overall in the summer months between May through July. There were always more successful projects than failed projects and than canceled projects for each of the months.

### Analysis of Outcomes Based on Goals
I performed this analysis through the Kickstarter dataset provided by using the countifs function and graphing in Excel to visualize the campaign outcomes based on funding goal amount for the "plays" subcategory.

I created a new sheet called "Outcomes Based on Goals" where I grouped the goal funding into buckets of funding amounts to better visualize the data. I used the Sum function to find how many projects were in each funding group bucket to calculate the percentage of successful, failed, and canceled projects. I created a chart called "Outcomes Based on Goal" to visualize the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis.

![](/resources/Outcomes_vs_Goals.png)

Looking at the line chart above, we can see that the most successful projects had funding goals less than $15,000 and between $35,000 to $44,999. The greatest percentage of failed projects were between $15,000 to $34,999 and greater than $45,000. 

### Challenges and Difficulties Encountered
I had one challenge in the "Analysis of Outcomes Based on Launch Date" step where I did not realize my pivot table had automatically grouped the data into months but I used this to discover how the grouping function worked.

I had another challenge in the "Analysis of Outcomes Based on Goals" where I needed to make sure I selected the right data to showcase on the graph. I solved this by selecting the specific columns I needed to showcase and compare.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
One conclusion I can draw is that Louise should for future theater projects aim to launch during the summer months, specifically on May if possible as this month showed the highest number of successful projects over other months. Another conclusion I can draw is that the chart shows a trend of more successful occuring as the launch date approaches May and then trending downward as it approaches December. The number of failed and canceled projects remain around the same through all the months.

- What can you conclude about the Outcomes based on Goals?
I can conclude that a theater project should aim to have a funding goal less than $15,000 and between $35,000 to $44,999 based on the data provided. The data shows there is a greater percentage of failed projects as funding goals are between $15,000 to $34,999 and greater than $45,000. The most successful funding goal show as those less than $1,000.

- What are some limitations of this dataset?
Some limitations of this dataset include limited sample of information as this dataset does not capture population data, rather a sample data. The dataset could be skewed by some projects so we would need to perform an IQR check to see how the dataset is overall.

- What are some other possible tables and/or graphs that we could create?
Some other possible tables and/or graphs that we could create include a Box and Whiskers plot to check for outliers and the skewness of the dataset and a bar graph to visualize the amount of each type of subcategory within the theater category. We could have gone in-depth into the theater category and broke it down based on subcategory so Louise would have a better understanding of how subcategory projects perform based on launch date and funding goal.
