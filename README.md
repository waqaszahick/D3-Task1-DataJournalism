# D3-Task1-DataJournalism
D3 Task-I: Data Journalism-D3 Dabbler

This is my over-all 15th, and first D3 assignment. In this assignment, my task was to analyze the current trends shaping people's lives, as well as to create charts, graphs, and interactive elements to help readers understand my findings such as health risks facing particular demographics. My information sources for this assignment, are the U.S. Census Bureau and the Behavioural Risk Factor Surveillance System.
The data set included with the assignment is based on 2014 ACS 1-year estimates: https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml. The current data set includes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."
In this assignment, I have utilized both: html and JavaScript.
As mandatory part of this the assignment, I was required to create a scatter plot between two of the data variables such as “Healthcare vs. Poverty” or “Smokers vs. Age”.
Using the D3 techniques, I created a scatter plot that represents each state with circle elements. I performed coding for this graphic in the “app.js” file; and pulled in the data from “data.csv” by using the “d3.csv” function. Apart from this, I performed the following tasks:
-	Included state abbreviations in the circles.
-	Created and situated the axes and labels to the left and bottom of the chart.
-	Used ”python -m http.server” to run the visualization in order to host the page at localhost:8000 in my web browser.