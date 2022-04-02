Overview of Project:
  An Analysis of Kickstarter Campaig was performed using Kickstarter data to help inform Louise about crowdfunding campaigns, and what factors may help her have a successful campaign for her play "Fever".

Analysis and Challenges:

  To perform this analysis, I created a pivot table and chart using the Kickstarter data. I filtered the data by the parent category, theater. I then placed the outcomes in the columns and the launch date in the rows.A potential challenge with completing this analysis is how to get the months to display correctly in the Outcomes Based on Launch Date Pivot Table. This data did not automatically appear as needed, I had to use the grouping function in Pivot Table Analyze menu to resolve the issue. 

Conclusions :
  The first conclusion that I draw from the Outcomes based on Launch Date Analysis is launching the campaign at a right time is important for it be successful.
The second conclusion is that December and January are the worst months to launch a Kickstarter campaign.


![image](https://github.com/morriscomia/kickstarter-analysis-/blob/4bf1b7fe2bdb7b59c81fbae9cab6b1d50d1039e0/Theater_Outcomes_vs_Launch.png%20.png)

Analysis and Challenges:

  By taking an initial look at the raw data I figured it had to be sorted and prepared for the analysis by creating a chart with goal amounts for the rows and the Number of Successful, Failed, and Cancelled campaigns as well as percentage of each of those in the columns. To find this data, I created COUNTIFS staments to pull data from the Kickstarter data tab. I then created a line chart with the goals on the x-axis and percentages on the y-axis. The chart gives a great visual representation of the data. A potential challenge was completing the COUNTIFS statements in the Outcomes Based on Goals Analysis. If unfamiliar with this formula, it is challenging to make sure to include all of the variables, especially to include the correct goal amounts in the formula.

Conclusions: 

The first conclusion that I draw from the Outcomes based on Goals analysis is that campaigns up to $5000 are the most successful. The second conclusion from this analysis is that campaigns of $45,000 and up are very unsuccessful.

![image](https://github.com/morriscomia/kickstarter-analysis-/blob/4bf1b7fe2bdb7b59c81fbae9cab6b1d50d1039e0/Theater_Outcomes_vs_Launch.png%20.png)
![Launch](https://github.com/morriscomia/kickstarter-analysis-/blob/6596b2609115e109a6608b7b263ed6028ba63901/Outcomes_vs_Goals.png)



Results

  Knowing which season and/or month to launch a kickstarter may be key to success. Data shows that successful theater campaigns were launched during late Spring/early Summer (May-June), whereas failed campaignes were launched during the Winter (December).

Limitationsof Data set: Information on the Genre of plays would have helped determine the success of plays and give better analysis to Louise. The dataset is from the year range - 2009 till 2017. If we had information about current data. We could have analyzed current trends.

A recommendation for additional tables or graphs : A clustered column chart can be used to show the outcomes based on Launched Date.
A stacked column, Clustered column chart can be used to show Outcomes based on goals.
