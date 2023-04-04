# Crodfunding-assignment

Background

Crowdfunding platforms like Kickstarter and Indiegogo have been growing in success and popularity since the late 2000s. From independent content creators to famous celebrities, more and more people are using crowdfunding to launch new products and generate buzz, but not every project has found success.
To receive funding, the project must meet or exceed an initial goal, so many organisations dedicate considerable resources looking through old projects in an attempt to discover “the trick” to finding success. The goal of this Challenge, was to organise and analyse a database of 1,000 sample projects to uncover any hidden trends.


Steps

Using the Excel workbook , I modified and analysed the sample-project data and try to uncover market trends.


* Using conditional formatting to fill each cell in the outcome column with a different colour, depending on whether the associated campaign was successful, failed, cancelled, or is currently live.


* Create a new column called Percent Funded that uses a formula to find how much money a campaign made relative to its initial funding goal.


* Using conditional formatting to fill each cell in the Percent Funded column according to a three-colour scale. The scale had to start at 0 with a dark shade of red, and transition to green at 100 and blue at 200.



* Creating a new column called Average Donation that uses a formula I had to find how much each project backer paid on average.


* Creating two new columns, one called Parent Category and another called Sub-Category, that use formulas to split the Category and Sub-Category column into the two new, separate columns.
    

* Created a new sheet with a pivot table that analysed the initial worksheet to count how many campaigns were successful, failed, cancelled, or are currently live per category.


* Created a stacked-column pivot chart that could be filtered by country based on the table that I created.


* Created a new sheet with a pivot table that analysed my initial sheet to count how many campaigns were successful, failed, or cancelled, or are currently live per sub-category.


* Created a stacked-column pivot chart that can be filtered by country and parent category based on the table that I created.


* The dates in the deadline and launched_at columns use Unix timestamps.


 * Created a new column named Date Created Conversion that will use this formulaLinks to an external site.  to convert the data contained in launched_at into Excel's date format.
   
   
 * Created a new column named Date Ended Conversion that will use this formulaLinks to an external site.  to convert the data contained in deadline into Excel's date format.
    
 * Created a new sheet with a pivot table that has a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and Years.


* Created a pivot-chart line graph that visualises the new table.


* Created a report in Microsoft Word, and answered the following questions:

1. Given the provided data, what are three conclusions that we can draw about crowdfunding campaigns?
2. What are some limitations of this dataset?
3. What are some other possible tables and/or graphs that we could create, and what additional value would they provide?



