# Kickstarter Analysis - Deliverable 3
###  **Project Overview**
- Louise needs help with an analysis of tabular data she has compiled of Kickstarter Campaigns around the globe. The compiled spreadsheet contains information regarding dates, funding goals, pledged funding, outcomes, type of campaign, etc.
- ### Kickstarter Campaign data and its purpose:
    1. Why are we analyzing this data?
    2. What is the goal and possible outcomes?
    3. What pieces of data can help build toward and obtain our goal(s)?
- Louise estimates she'll need around $12,000 for her campaign but needs help determining if this is a reasonable estimate.



### **Analysis**
So I have all this data and created a goal to help Louise calculate how much money she will need to raise. 

I open up the spreadsheet and realize there needs to be some formatting and filtering that needs to occur to fully comprehend the spreadsheet.

As I got a feel for the data, questions started becoming clear:
- What country should the analysis be based on?
- What category/subcategory should we focus on?
- How often did successful (or failed) campaigns reach their goal?
- What time of the year are the majority of successful/failed campaigns launched?

With these questions in mind, we can begin filtering our data and set parameters that allow us to draw conclusions. **[Pivot Tables](https://support.microsoft.com/en-us/office/create-a-pivottable-to-analyze-worksheet-data-a9a84538-bfe9-40a9-a8e9-f99134456576)** are a great way of setting parameters and summarizing data in an efficient manner. In addition to this, **[Pivot Charts](https://support.microsoft.com/en-us/office/create-a-pivotchart-c1b1e057-6990-4c38-b52b-8255538e7b1c)** are a great way of visualizing pivot tables, which is important in finding patterns.

I was able to use these tools in my analysis to filter by country & category/subcategory to summarize and visualize the number of failed, canceled and successful. Now that I practiced comparing outcomes to categories/subcategories, it was time to compare outcomes based on the launch date using the same methods, using months on the x-axis.

<p align="center">
  <img src="https://github.com/lawnshogan/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png" width="700"/>
</p>

From here, Louise needed to know about the outcomes based on goals. Creating a new table, I was able to create ranges and use the =Countifs formula to create a summary of outcomes based on pledged dollars for 'play' related Kickstarter Campaigns.

<p align="center">
  <img src="https://github.com/lawnshogan/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png" width="700"/>
</p>

### **Challenges**
The first thing that I will say is every challenge I encountered was fixed by a Google Search. I'm realizing how important the context is when you are searching for answers. This was very helpful and helped me learn. 

I struggled at first with Pivot tables, however they quickly became easier for me after some practice and knowing how to look at the data to make sure you are answering the correct questions.

I especially enjoyed learning about the different Excel formulas and applying them to the analysis. Excel makes math very easy, as long as you are entering in your code correctly!

### **Results**
Theater Outcomes by Launch Date
- The highest amount of successful campaigns in the Theater category were launched in May.
- The fewest successful campaigns in the Theater category launched in Decemeber.

Outcomes Based on Goals

- The campaigns that failed had had higher goals that could not be met.


It would be interesting to see which of these are still active and profiting, which could be used in another analysis in itself. 

I think it's important to look at the Percent funded and Average Donation size as well. A pivot table could be created to show average donation size for successful vs failed campaigns. I believe it would also be important to show the average percent of funding for successful campaigns.

I noticed there is a 'Staff Pick' column in the spreadsheet as well. You could use this to not only filter out successful campaigns, but to go even further and only include those that were picked by staff.