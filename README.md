# Internet Sales Analysis Dashboard

[Check this link to see the full dashboard](https://app.powerbi.com/view?r=eyJrIjoiOTE0MDU2YzctYTNiZi00NmUwLTgwOGEtZmU1YzM5YzhmNjA5IiwidCI6IjM1NDMyZDE1LTZjMGYtNDVhZS1iYzg5LTMzOGIwMGJlYmJiYSIsImMiOjh9&pageName=ReportSection)

![image](https://user-images.githubusercontent.com/113878177/200689791-6c60399c-23f1-4423-bb14-8cb4f20ecf8a.png)

## Project overview

In this project, we have a scenario of receiving a task from the Sales Manager:
  " Hi Natalie, I hope you are doing well. We need to improve our internet sales reports and want to move from static reports to visual dashboards. Essentially, we want to focus it on how much we have sold of what products, to which clients and how it has been over time. Seeing as each sales person works on different products and customers it would be beneficial to be able to filter them also. We measure our numbers against budget so I added that in a spreadsheet so we can compare our values against performance. I've attached the budget for 2022 and we usually look 2 years back in time when we do analysis of sales. Let me know if you need anything else! - Steven "
    
The databases was used in this scenario is from [AdventureWorks sample databases](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms)

## Processes

### Create user stories

To ensure the dashboard we're creating is actually useful to the audiences (Sales Manager, Sales Representative), it's important to first analyze the business objectives and write user stories. Please check the MS Word file "Business Demands Overview" for this.

### Data cleaning

For the dashboard, I decided to use 5 datasets. I've attached the queries for this step.
 
 1- DIM_Calendar
 
  ![image](https://user-images.githubusercontent.com/113878177/200687130-ffd41d77-7fc3-4516-b9a0-ada57c3ea394.png)
  
  
 2- DIM_Customer
 
  ![image](https://user-images.githubusercontent.com/113878177/200687603-159d4220-3467-458e-b825-dfa4a458b7d3.png)
  
  
 3- DIM_Product
 
  ![image](https://user-images.githubusercontent.com/113878177/200687932-890440a9-7128-4912-83de-e91c8bd66bbc.png)
  
 4- FACT_InternetSales
 
  ![image](https://user-images.githubusercontent.com/113878177/200688036-b3431228-c11f-4f6c-9a65-464e0ab78c03.png)

  
 5- FACT_SalesBudget (send over file)
 
  ![image](https://user-images.githubusercontent.com/113878177/200688503-7045984d-633c-4fad-ac7b-dd158556a890.png)
  



