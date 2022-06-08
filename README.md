# kickstarter-analysis

An Analysis of Kickstarter Campaigns

# Module 1 Challenge

# Overview of Project - Purpose and Background

  The purpose of this challenge was to assist Louise in understanding the relationship between outcomes and launch date, and outcomes and goals by using her kickstarter data. In other words, Louise recruited our team to perform analyses on her crowdfunding project data. After seeing her play Fever approach its fundraising goal rather quickly, she realized she may want to know more about launch dates, goals and their possible impact on the outcomes of her campaigns.

# Overview of Analysis

  In order to best help Louise understand the relationships present in her data, we needed to create visualizations that were easy for Louise to interpret. Two analyses were performed: Analysis of Outcomes Based on Launch Date and Analysis of Outcomes Based on Goals.

## Analysis of Outcomes Based on Launch Date

### Attachments - Outcomes Based on Launch Date

## Analysis of Outcomes Based on Goals

### Attachments - Outcomes Based on Goals

# Challenges

  One challenge that we faced along the way was during the creation of the Line chart visualization for Outcomes Based on Goals. After creating a table for this analysis, we noticed that the number of canceled campaigns within the plays subcategory was zero. We were not expecting to find this in our analysis, so we went back into the raw data to filter and confirm that the analysis was performed correctly, and the calculated zero values were accurate. 

  Additionally, when creating the line chart for Outcomes Based on Goals we encountered an unforeseen barrier. Initially, the chart that generated from the 8 column table included variables that we were not interested in analyzing. For example, columns B:E were necessary in calculating the values within columns F:H, but did not need to be included when generating the line chart. After realizing that the line chart was not the visualization we were looking for, we clicked on the line chart, which revealed the highlighted portions of the related table. The table's highlighted areas included columns B:E, which resulted in a line chart that was not easy to understand, or helpful to Louise. 
  The adjustment was simple - We dragged the highlighted areas so they would no longer include columns B:E, only F:H and column A (which represents the values on the x-axis). After completing this drag action, the chart adjusted automatically to show only outcomes based on goals, without any additional data points or factors.

# Results

## What are two conclusions you can draw about the Outcomes based on Launch Date?

  The first conclusion that can be drawn based on the analysis and visualization of outcomes based on launch date is that the highest amount of successful campaigns in the theater category were launched in May. Another conclusion we can draw from this analysis is that none of the theater campaigns launched in October were canceled. 

## What can you conclude about the Outcomes based on Goals?

  When looking at the analysis for outcomes based on goals, we paid attention to the plays campaigns goal ranges with the most total projects. In other words, there were 534 plays campaigns within the range of 1000 to 4999. 73% of plays campaigns with goals within this range were successful. Another observation from this analysis is that there were less plays campaigns with higher goal ranges, and more plays campaigns with lower goal ranges. 

## What are some limitations of this dataset?

  We do not know much about how this data was collected. For example, if Louise manually input the data herself she could have made a mistake which would result in inaccurate data points. If the data was collected automatically by some type of machine, we may be able to trust each data point more than if Louise spent hours inputting this data by herself after a long day. 
   Additionally, there are other factors outside of the ones within this data set that may impact the outcome of her campaigns. For example, her campaigns are accross many different countries. All of these countries have different holidays and these holidays could have impacted launch dates in certain countries. Factors external of her data set may have had impact that we would not be able to understand through analyses given a lack of data points for these factors. 

## What are some other possible tables and/or graphs that we could create?

  Additional analyses would be created for additional questions that Louise may have for our team. For example, Louise asks: Does having more backers yield more successful campaigns? We could answer this questions for Louise by analyzing the relationship between backers_count and outcomes. The best way to display this data would be first, with a pivot table. We could create a new table with a column for backers_count_range. This variable would be similar to the column we created in the outcomes based on goals analysis for goal ranges. Once we have this new column, we can get a count of backers within each range. We could then drag the outcomes variable to columns, and count of outcomes to values. This would give us a pivot table that shows campaign outcomes in relation to the amount of backers for that campaign. If we wanted to add a visualization to this analysis, we could insert a line chart that has backers_count_range on the x-axis, and percentage of successful, failed and canceled campaigns on the y-axis. 
