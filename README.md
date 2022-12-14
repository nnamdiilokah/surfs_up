# surfs_up
**Performing Weather Analysis Using SQLite, SQAlchemy and Python**

  ## Overview of Project
  The purpose of this project is to carry out an analysis using SQLite and SQAlchemy to gather June and December temperature trends in Oahu, Hawaii for a potential investor who wants to establish a surf shop. The potential investor requires this statistics in order to determine if the surf and ice cream shop business is sustainable year-round.

  To perform this analysis, the following steps will be carried out:

  + Run two separate queries to retrieve all temperature data for the months of June and December.
  + Store the retrieved temperature for June and December in a list.
  + Create a DataFrame from the list of temperatures.
  + Generate the summary statistics for June and December temperatures.

  ## Results
  
  Our analysis provided three key differences in weather between June and December
  
  Summary Statistics for June temperatures is shown in the image below:

  ![june_summary](https://github.com/nnamdiilokah/surfs_up/blob/main/june_summary.png)

  
  Summary Statistics for December temperatures is shown in the image below:

  ![december_Summary](https://github.com/nnamdiilokah/surfs_up/blob/main/december_summary.png)


  + The month of June has higher mean temperature than the month of December. June has a mean temperature of 74.94 degrees whereas the month of December has a lower mean temperature of 71.04 degrees.

  + December has a lower maximum and minimum temperature compared to the month of June. December's maximum temperature was 2 degrees less than June's maximum temperature of 85 degrees.  Also, December's minimum temperature of 56 degrees is 8 degrees less than the June minimum temperature of 64 degrees.
 
  + When comparing standard deviations, there is approximately 0.5 difference between the two months. June resulted in a standard deviation of 3.257 compared to December's standard deviation of 3.746.
  
   
   ## Summary

   Based on the results obtained from our data analysis, Oahu in Hawaii presents pleasant temperatures for surfing with average temperature between 74.94 and 71.04 for June and December and the Max temperature extremely plasant on the island. At such it is safe to advise and recommend that the surf and ice cream shop business will be sustainable all year-round.

   We can run additional queries over our data to retrieve precipitation statistics to aid in business decisions.

   Also, additional query can be run to determine the fluctuations in temperature and to assess if there are outliers.
