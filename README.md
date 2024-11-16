# kickstarter_Project_Analysis

### ✅️Introduction
In this notebook I will share my analysis of a dataset of roughly 366,000 Kickstarter projects. Kickstarter is one of the most popular platforms for promoting and bringing to life creative projects, from Music, Art, Film and Games, you name it. Each project does this by seeking funding from the Kickstarter crowd to support their idea and hopefully see it succeed. However, many projects fail and I will walk you through my analysis through data exploration with SQL to reveal insights into Kickstarter projects and their success and failure. I will then visualise the data in Power BI to present my findings and draw recommendations to my summary question, which you will find further down.

### ✅️Project Overview:

Crowdfunding is a way of raising money to finance projects and businesses. This project presents analysis of projects from Kickstarter based on various aspects such as the amount raised, categories, backers count, time range. The goal is to assess the success rate of the projects.

### ⚒️Visualization Tools
+ **Excel** 
+ **MySQL** 
+ **PowerBI** 
+ **Power Query**
+ **Database :- Excel**

### ⏬️Steps Involved

  + **Data Understanding** : Assessing the dataset to understand kind of data, format, and identifying common columns in case of multiple tables.

  + **Data Cleaning** : Utilized Power Query Editor to clean the data by removing null values and special characters.

  + **Data Modelling** :Employed data modeling using Power Pivot, to establish relationships between three tables.

  + **Data Visualization** : Created a interactive dashboard with six Key Performance Indicators (KPIs), four slicers, and charts using Pivot Tables.


### 📌Key Insights from the Dashboard

+ This dashboard gives an overview about one of the many crowdfunding platforms, Kickstarter. This is a platform for generating funds for a project.
+ Multiple outcomes for a project can be observed, viz., Successful, Failed, Live, Purged, Suspended and Cancelled. It can be observed that the success of a project is low in comparison to failure, suspension and cancellation put together, which is concerning for a business. Among the many reasons for suspension, lack of trust and non-transparency in disclosing relevant information about the project or the creator, as well as presenting others' work as one's own, are significant factors. 
+ In the year 2009, there were only 1310 projects, which have increased year on year.
+ There was a significant increase observed in 2014 and 2015, with peaks of 59.16K and 58.1K projects, respectively.
+ In the subsequent years, there was a slight decline to 46.16K projects, but the number of projects remained consistently high, staying above 37K.
+ By 2019, there was a drastic drop to only 1.52K projects.
+ **Successful (140,293 projects)**: A large number of projects achieved their goals, but fewer than the failed ones, which accounts for **38.3%** of the total projects.
+ **Initial Struggles (2009)**: The journey began with a low success rate of only 0.41%, highlighting initial challenges and learning curves.
+ **Rapid Growth (2014)**: Achieved a peak success rate of 13.73%, showcasing effective strategies and improved execution.
+ **Decline in Success (2019)**: Faced a steep decline to just 0.03%, necessitating an analysis of underlying issues and challenges.
+ **Analysis Needed**: The fluctuating trend underscores the need for comprehensive analysis to understand the factors influencing these outcomes.
+ **Future Strategies**: Focus on identifying and mitigating issues to enhance the success rate in the years to come.

### 📊Poewr BI Dashboard
<img width="800" alt="Screenshot 2024-11-13 155130" src="https://github.com/user-attachments/assets/6600ebe9-2962-423f-b032-e46743680d14">

### 📈Succsessful Project Dashboard
<img width="800" alt="Screenshot 2024-11-13 155207" src="https://github.com/user-attachments/assets/328008a2-db3f-4b83-b748-983af4227d83">

### Data Modelling
<img width="800" alt="Screenshot 2024-11-13 160042" src="https://github.com/user-attachments/assets/6953f4bd-b599-463e-aa66-98d9a84cba9e">

### 📊Excel Dashboard
<img width="855" alt="Screenshot 2024-11-13 163222" src="https://github.com/user-attachments/assets/9638bd59-0e4f-4580-a622-b38fd35fbc47">

### Conclusion 
The average success rate of a project at Kickstarter is 36% and the median goal is 5K Dollars (the median was calculated only for projects financed in dollars)
An entrepreneur who wants to fund projects in the category of music or other art categories should consider starting a Kickstarter project because the average rate in these categories are above 55%. However, technology projects are less successful on this platform.
Between the years 2014 and 2015 there was growth in the number of projects. The growth happened in most of the categories and especially in the technology category.
This analysis can be further elaborated upon by examining whether the project goal amount or country of origin affect the success of the project.
