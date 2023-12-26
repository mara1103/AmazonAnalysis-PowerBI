# Data Analysis / Reporting for an E-commerce company
### Project Overview

This Business Intelligence project is based on the "E Commerce Sales" dataset ("Amazon Sales Report.csv"), published on the Kaggle platform, mentioning the original author Anil and [source](https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data). It contains details about orders and products. I analyzed the company's sales and revenue trends for the period 31.03.2022 and 29.06.2022. By building interactive dashboards, essential information can be revealed and used for possible subsequent business decisions.  
  
### Tools :
- Excel - Data preparation 
- SQL Server / SQL Server Management System - Normalisation & Data analysis
- Microsoft Power BI - reporting / dashboarding

### Data preparation
I decided to **_normalize_** the data to make it easier to add new records to the database and read the existing ones, without having duplicate or ambiguous elements.
To respect first normal form (**_1NF_**), each attribute must have atomic values. I used **Excel** to split by delimiter the promotion-ids column.
Furthermore, I created a new database and imported the dataset into the **SQL Server Management System (SSMS)**. To eliminate functional and transitive dependencies (**2NF & 3NF** ), I created new tables/entities and the corresponding primary and foreign keys. 

  The final ER Diagram looks like this:
  ![image](https://github.com/mara1103/PowerBI_project/assets/53566633/5b8f43a4-69f4-433d-91ae-c0456a6f7a88)

### Reporting 
#### Power BI
For a better understanding, through the introductory report I have added a brief description of the E-commerce company, as well as of the data to be analyzed. The dataset includes details related to Amazon India's Q2 2022 sales. I considered it relevant to add financial statistics of the company at global level, taken from the source: ["Amazon.com, Inc. - Amazon.com Announces First Quarter Results (aboutamazon.com)"](https://ir.aboutamazon.com/news-release/news-release-details/2023/Amazon.com-Announces-First-Quarter-Results/). I used Power BI functions to add a table from web, similar to a web scraping technique. The chart is based on the global data, and the cards on the initial dataset. 

![image](https://github.com/mara1103/PowerBI_project/assets/53566633/5e50e5fd-df1d-4178-b465-56dd26e0bbd6)

Similarly, the following reports will reveal information related to the products purchased, the locations where the orders were distributed, total sales, prices, and finally a sales prediction exercise for the next month.

You can find the whole project here : 

