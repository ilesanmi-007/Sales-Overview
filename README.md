# Sales-Overview
----
## Introduction

Engr BIOS Group of Company, a purely fictional enterprise, has made a name for itself as a leader in technological research. However, this is not the extent of its prowess as the company is also a leading contender in the highly competitive market of bike sales, even vying with the likes of established brands such as Mercedes Benz and D&G.

As a company that prides itself on its sales performance, Engr BIOS Group is continuously seeking ways to monitor and evaluate the progress of its sales. To achieve this, the company's sales manager reached out to Mr. Ilesanmi Samson, the lead data analyst, in a bid to obtain detailed insights and comprehensive data analysis.

Mr. Samson, a proficient and highly skilled data analyst, was tasked with the responsibility of providing the sales manager with detailed reports and statistics on the company's sales performance. This would include analyzing sales trends, identifying opportunities for growth, and determining potential threats that could impact sales.

Engr BIOS Group recognizes the value of accurate data analysis in decision-making and has thus invested heavily in acquiring the best talent in the field. With Mr. Samson's expertise, the company is well-positioned to make informed decisions that will not only enhance its sales performance but also solidify its position in the highly competitive market of bike sales.

----


Mail | 0
:---------------------------------------------:|:-----------------------------------------:
![image](https://user-images.githubusercontent.com/68794860/233706187-940a9a13-fa27-40e0-bea0-5c62857529fb.png) |

# Business Demand Overview:
-	Reporter: Steven – Sales Manager
-	Value of Change: Visual dashboards and improved Sales reporting or follow up or sales force
-	Necessary Systems: Power BI
-	Other Relevant Info: Budgets have been delivered in Excel for 2021

### Key points:
1.	Total sales
2.	Sales per product
3.	Sales per Customer
4.	Sales over time

----

0 | Business Overview
:---------------------------------------------:|:-----------------------------------------:
 0 | ![image](https://user-images.githubusercontent.com/68794860/233706219-52dd8e6b-f16d-4dab-a537-59b25be3aeb1.png)

----
## Skill
PowerBI and SQL
----

## Steps taken
1. Used SQL to extract data from the SERVER
2. Performed Data Cleaning
3. Performed ETL in PowerBi
4. Made necessary visuals

# **SQL**

The following are the SQL Queries written to extract data from the server. As stated in the mail that the Budget given was of 2021 and it was necessary to perform analysis two years back in other to see the trend. Hence the visuals made are of year 2019 - 2021.

Data is extracted from four tables. And these are:
- Fact table: Fact_internet
- Dimension table:
1. Dim_Product
2. Dim_Customer
3. Dim_Calendar

Just to note that the difference between Dimension table and Fact table are that:
1. Fact tables contain quantitative data (facts) about a specific event or transaction, such as sales figures or website clicks, while dimension tables contain descriptive data about the various aspects or attributes of the event, such as the customer, product, or time period.

2. Granularity: Fact tables are usually at a lower level of granularity than dimension tables. For example, a fact table might have individual sales transactions, while a dimension table might have information about each product sold, such as its name, category, and manufacturer.

3. Joins: Fact tables are often joined to one or more dimension tables to provide additional context and meaning to the quantitative data. Dimension tables can be used to filter and group the data in the fact table, making it easier to analyze and understand.

---
# **SQL**
To get the dataset to use, i made use of the adventure works DB on Microsoft Server. I extracted the necessary columns that would help with the business objective.



----
# Power BI
The tables had to be joined together withe their common primary key and below is the data model of the tables:

![image](https://user-images.githubusercontent.com/68794860/234278097-a6ecdab8-b536-4099-8035-8795367ee5bc.png)


## **Sales Overview**
![image](https://user-images.githubusercontent.com/68794860/234279545-efe93408-c93c-440a-864b-a9b1abed8e11.png)

The Sales Overview dashboard shows the following:
1. Sales made and Budget - It shows the Total sales made per year and the allocated Budget per year. It also shows the if more sales were made than the allocated budget.
2. Sales by Product
3. Top 10 Product
4. Top 10 Customers
5. And a trend of Sales and Budget per month. This is to observe the progress of sales per month

## **Customer Details**

![image](https://user-images.githubusercontent.com/68794860/234284764-5162928a-7650-4cbf-b2b0-e8e7b9504272.png)

## **Product Details**

---
The other two visuals are for more details on the customer and product. It shows more of the top sold products and top customer.
