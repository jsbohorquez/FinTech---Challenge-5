## Challenge-5 
# Financial Planning Tools and API Sims

## Overview
This program [financial_planning_tools.ipynb] contains code with examples of accessing financial data through an API source (Free Crypto API and Alpaca SDK API) and implementing the data to run various financial planning tools such as current value, future projections, and financial projections for retirement planning at 30 years and 10 years.

## Technologies Used
The libraries and dependencies used in this program are listed in the first cell of the program which are: OS, Requests, JSON, Pandas, DOTENV, alpaca_trade_api, and MCForecastTools(python file for this is included with program folder). 


## Program Layout
This program is divided into two parts which are as follows:

**Part 1** - Creating Financial Planner for Emergencies
            Cryptocurrency and Stock/bond financial data is accessed and evaluated to create an emergency fund based on pre-set client information (number of shares held, number
            of cryptocurrencies held, salary)
            
**Part 2** - Creating Financial Planner for Retirement
            Stock/bond financial data is accessed and evaluated, data is cleaned and primed for use with MonteCarlo Simulation to project value of retirement portfolio in 30 
            years and again in 10 years. Data is processed and displayed in projected visuals as well as statistical summaries for interpretation.
          
## Author
Juan Bohorquez

