# Regression analysis to examine the relationship between player wage spending by teams and win percentage
In week 5 of the University of Michigan's Foundations of Sports Analytics: Data, Representation, and Models in Sports we have looked at the role of a season’s performance (lagged win percentage) and team specific fixed effects. Salaries, lagged win percentage and some, if not all, team specific fixed effects were found to significantly affect win percentage for the Indian Premier League (IPL). 

## Here are the steps you need to take:

1. Load the data

2. Create the sum of salaries in each season

3. Create a variable for team salary divided by total salaries for that season (relsal).

4. Create a value for win percentage. Define win percentage as wins divided games with a result (= games played minus games with no result). 

5. Create the lagged value of win percentage for each team

6. Regress win percentage on:
a) Relsal
b) Relsal + lagged win percentage
c) Relsal + lagged win percentage  + team fixed effects
