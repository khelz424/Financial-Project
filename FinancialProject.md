Financial Project

PROJECT OVERVIEW

This data analysis project provides insights about the financial performance of specific products in different countries. Focusing on the Summary,Country and Product analysis reports for the 2013 and 2014 period. These insights can be used to make recommendations on how to maximise their revenue in the next financial period.
The data was a financial excel workbook file. It included information about the different products performance in the following countries: USA, Germany, France, Canada, and Mexico.

Below is a list of visuals I created: 

Summary Report

Product Analysis

Country Analysis




STEPS FOLLOWED

1. Loaded the data into PowerBI.
2. No data cleaning was done as they were no errors,formatting issues,duplicates,nulls or empty rows.
3. Created a new Date Column:


   3.1. Created a new table called Calendar
   
   3.2. Copied the date column from the Financials table
   
   3.3. Clicked on calculated column to showcase the dates from the first of the month to the last day of the month 
        for both years


    Snapshot of Calculated Column:


   ![Screenshot (25)](https://github.com/khelz424/Financial-Project/assets/141655852/5bf91776-ded5-435b-8390-b74b66e9f38b)

   
4. Created two measures that calculate the total revenue and gross profit margin.


Snapshot of Revenue measure:

This measure uses the SUMX function to calculate the revenue by multiplying the units sold and sales price from the financials table.

![Screenshot (53)](https://github.com/user-attachments/assets/2cdf70e8-7a42-4eaa-9405-9243441ea59d)


 
Snapshot of Gross Profit Margin:

This measure uses the DIVIDE function to calculate the gross profit margin by using the revenue measure created previously with the cost of goods sold from the financials table.

![Screenshot (51)](https://github.com/user-attachments/assets/b4ce61b5-080f-43c9-8656-dd82dd7890d1)


VISUAL 1: Summary Report

The visuals provided showcase a summary of the revenue and profit for the different countries and products.

Snapshot Of Visual:


![Screenshot (48)](https://github.com/user-attachments/assets/be9f54be-8131-4f8c-8147-cf9bb5cff6d4)


VISUAL 1.1: Total Revenue and Profit by Month

I chose a Line and Stacked Column chart whcih provides a summary of the total revenue represented by the column charts and the profit represented by the line chart displaying insights per month. This was done to show the relationship between the revenue and profit per month.


VISUAL 1.2: Profit By Country

I chose a Clustered Column chart because it a clear comparison between the gross sales and profit per country.


VISUAL 1.3: Profit By Product

I chose a Stacked Bar Chart because it represents the different prdocuts very clearly by showcasing the profit levels through the different sizes of the shapes.


REPORT OBJECTS


SLICER 1: Year,Quarter,Month

I included a slicer where a user will be able to filter the visuals based off the Year,Quarter, and month.

BUTTONS: More Details

I included two buttons that navigate to pages that provide more detailed information regarding the country or product clicked on.


VISUAL 2: Drillthrough - Country Analysis

This page is linked to the Country by Profit visual where a user selects a specific country and then clicks on the button which navigates to the Country analysis page which will showcase detailed information about that specific country.

I chose a table as the visual because it provides a simple format to view detailed information regarding numeric values.

Snapshot Of Visual:


![Screenshot (50)](https://github.com/user-attachments/assets/c4e78c7c-33e6-4d8c-b82a-0b117293aa2c)


VISUAL 3: Drillthrough- Product Analysis

This page is linked to the Product by Profit visual where a user selects a specific country and then clicks on the button which navigates to the Country analysis page which will showcase detailed information about that specific country.

I chose a table as the visual because it provides a simple format to view detailed information regarding numeric values.

Snapshot Of Visual:


![Screenshot (49)](https://github.com/user-attachments/assets/80baa575-a82f-4e56-a5e1-876af3813106)


CONCLUSION

In conclusion, this data analysis project has analysed and explored ways to utilise the data to create new columns and measures to facilitate in the analysis. Which has lead to creating visuals with useful insights that users can make informative decisions about improving their financial performance.
