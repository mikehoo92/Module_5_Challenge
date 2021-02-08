# Retirement Portfolio Analysis
## *Evauluating Financial Health*

This notebook offers a platform that helps credit union member the ability to assess their retirement portfolios. They will first be able to assess their monthly budgets and visualize their current savings to see if they have enough in their emergency funds. Second, they will be able to forecast the performance of their retirement portfolio in 30 years using data from the last 10 years.

![](Images/5-4-monte-carlo-line-plot.png)

---

## Technologies

This project uses a Jupyter Notebook in Jupyter Lab with the following libraries:

- Pandas: to help with the robust amount of features that will help analyze and organize the data.
- Alpaca API: via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.
- Requests: to use the functions as instructions to the API. 
- JSON: to work with files in the JavaScript Object Notation (JSON) format, the standard for API responses.
- dotenv: to access our API keys and environment variable from the .env file.
- Alpaca_trade_api: Alpaca is the API for stock trading. With the Alpaca SDK, we can interact with the Alpaca API.
- MCForecastTools: contains multiple functions and parameters that help us configure, run, and evaluate a Monte Carlo simulation
- %matplotlib inline: for plotting the dataframes to conduct a visual analysis.

---

## Usage

To succesfully run this notebook, please be sure to import the required libraries and dependencies:

```
import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation
```

---

## Contributors

Michael Husary was the main contributer along with fellow classmates and the educational staff. 

--- 

## License
*(Not sure if a license was required on this Challenge)*


MIT
