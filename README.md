# session-33-Assignment-2
DATA ANALYTICS WITH R, EXCEL AND TABLEAU SESSION 33 ASSIGNMENT 2

SESSION 33: TABLEAU DESKTOP (CONTD.)
Assignment 2



5. Problem Statement 
1. Create a Filled map by using the column State. Denote each state with different colours. 
2. Show the State Name and Total Sales in the labels 
3. Show the tooltip with State Name, Profit and Sales 

Answer: -

The following steps provides step by step to complete the tasks. The last graph shows the tooltip with state name, profit and sales as per the requirement
1. In Tableau, open a new workbook and connect to the Sample-Superstore data source.
2. On the Data Source page, click Sheet 1 to go to a new worksheet.
3. In the Data pane, under Dimensions, double-click State.
Tableau creates a symbol map, with a data point for each state in the Sample-Superstore data source.
4. On the Marks card, click the Mark-type drop-down and select the Map mark type.

5. From Measures, drag Profit to Colour on the Marks card.
6. From Measures, drag Latitude (generated) to the Rows shelf, and place it to the right of the other Latitude field.
6. You should now have two identical map views.
7. On the Rows shelf, right-click the second Latitude field and select Dual Axis.
The second map is now layered on top of the first map. There are now three drop-downs on the Marks card: 
one for each map view, and one for both views (all).
 These are three separate marks cards that you can use to control the visual detail for each of the map views.
8. On the Marks card, click one of the Latitude (generated) tabs, and then click the Mark type drop-down and select the Pie mark type.
9. From Measures, drag Sales to Size on the Latitude (generated) Marks card you selected.
The Sum of sales for each state is shown as text.
10. From Dimensions, drag Category to Colour on the same Marks card.
If the size of the pie charts is too small, click Size on the Marks card to adjust the size.
The map view now shows the sum of profit, as well as the sum of sales for each category, for each state.
11. . Show the State Name and Total Sales in the labels 
12.  Show the tooltip with State Name, Profit and Sales 
13. This provides the output as per the Assignment requirements.
