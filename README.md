## Financial Planning Tool
This challenge will create 2 financial applications in one Jupyter Labs Notebook. One will be an emergency fund planner, the other will use Monte Carlo simulations for retirement planning. 

---

## Technologies

This program/notebook should be viewed in jupyter lab, and the following libraries were used:
OS,
Requests,
Pandas,
Numpy,
Matplotlib,
Json,
Dotenv,
Alpaca Trade API,
MCForcastTools

---

## Installation Guide

This file requires Alpaca keys to access the SDK. The keys need to be stored as variables in a file called '.env' which should be located in the same folder as the 'financial_planning_tools.ipyn' file.
The following syntax should be used for the Alpaca keys:

ALPACA_API_KEY="your key here"
ALPACA_SECRET_KEY="your key here"

---

## Usage

This notebook is static from an investments perspective. The ammount of Crypto and quantity of Stock and Bond mutual funds are fixed. The values are calculated using prices obtained through the Alpaca SDK and the Free Crypto API. 

The Crypto prices will automatically update when these cells are run
![bitcoin](Images/btc_response.png?raw=True)
![etherium](Images/eth_response.png?raw=True)

If you want to compare values from the same trade date, you'll want to update the start and end dates for the stock and bond SDK call here to match the date of your crypto data:

![update the date](Images/date_update.png?raw=True)

The pie chart can be hard to read in dark mode. If you want to see the lables, try setting your jupyter lab theme to light mode:
![dark](Images/pie_dark.png?raw=True)
![light](Images/pie_light.png?raw=True)


---

## Contributors

Neil Mendelow - https://www.linkedin.com/in/neil-mendelow/

---

## License

This code is covered by the MIT license.