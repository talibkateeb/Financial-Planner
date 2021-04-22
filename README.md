# Financial-Planner

In this project I was tasked with creating a Financial planner for credit union members in order to be used in two ways:

1. A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

2. A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.


---


## Technologies


Python 3.7.10

Jupyter Lab 3.0.11

Jupyter Notebook 6.2.0

Pandas 1.2.3

Matplotlib 3.3.4

Alpaca API 

Python Requests 2.24.0

JSON

python-dotenv


---


## Installation Guide

To install required libraries and APIs run the following commands:

    pip install pandas

    pip install python-dotenv

    pip install alpaca-trade-api


Install Jupyter with Anaconda. Anaconda also comes with Requests and JSON pre-installed.

To run Jupyter Notebook run this command in directory with notebook file:

    jupyter notebook financial_planning_tools.ipynb

You must also generate your own Alpaca API keys and place them in a .env file in the same directory as the project. 

Example text in file:

    ALPACA_API_KEY = "Your Alpaca API key here"
    ALPACA_SECRET_KEY = "Your Alpaca Secret key here"

---


## Usage

Once you run the Jupyter Notebook, click on the first cell then hit:

    Shift + Enter

keys to run the first cell. Keep hitting those keys to run each cell after that or click the Run button to run the entire program.

You can change values such as how many Bitcoins or Eth coins are in your wallet, as well as the number of shares you own for the stocks. 
You can also tweak the weights to see what different weights produce. Changing these values can give you different results that help you in understanding your portfolio better.

---

## Example

Running these two cells will first configure the Monte Carlo simulation to forcast 30 years cumulative returns, show the first 5 rows of the dataframe, then run the Monte Carlo simulation. 

![Example](https://github.com/talibkateeb/Financial-Planner/blob/main/Example.png)

---
## License

[Click here to view](https://github.com/talibkateeb/Financial-Planner/blob/main/LICENSE)
