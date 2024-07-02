# Project Name: Portfolio Optimization


Portfolio optimization is a process in 
which an investor chooses their assets 
to optimize on one or more specific 
objectives. In this project we implement Monte Carlo simulations to find the minimum variance portfolio and observe the Markovitz bullet and calculate the Sharpe ratio.

## Project Description

The Efficient Frontier:
The efficient frontier is the set of optimal portfolios that offer the highest expected return for a defined level of risk or the lowest risk for a given level of expected return. Portfolios that lie below the efficient frontier are sub-optimal because they do not provide enough return for the level of risk. Portfolios that cluster to the right of the efficient frontier are sub-optimal because they have a higher level of risk for the defined rate of return.

In order to calculate the efficient frontier, we need to have an estimate of the expected returns and the covariance matrix for the set of risky securities which will used to build the optimal portfolio. These parameters are difficult (impossible) to forecast, and the optimal portfolio calculation is extremely sensitive to these parameters.

Sharpe Ratio:
The Sharpe ratio was developed by Nobel laureate William F. Sharpe and is used to help investors understand the return of an investment compared to its risk. The ratio is the average return earned in excess of the risk-free rate per unit of volatility or total risk. Subtracting the risk-free rate from the mean return allows an investor to better isolate the profits associated with risk-taking activities. Generally, the greater the value of the Sharpe ratio, the more attractive the risk-adjusted return.

This project focuses on generating the Minimum Variance Portfolio by applying portfolio optimization techniques to a diverse selection of Indian stocks. The project provides a deeper understanding of concepts such as CAPM, Sharpe ratio, and the practical application of quantitative finance in the industry.


The project involves the following key activities:

- Perform portfolio optimization to generate the minimum variance portfolio using a diverse selection of Indian stocks.
- Research and study various concepts like CAPM, Sharpe ratio, Risk vs Reward, Efficient frontier, and Beta factor.
- Create an efficient portfolio using a wide range of Python libraries such as yfinance, pandas, numpy, and matplotlib.

## File Description

- `Portfolio_Optimization().py`: This file contains the code for performing portfolio optimization and generating the minimum variance portfolio.

## Getting Started

To run the project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/aaravchanani4/Portfolio_optimisation.git`
2. Install the required dependencies.
3. Run the `Portfolio_Optimisation().py` script: `python Portfolio_Optimisation().py`

## Dependencies

The project requires the following dependencies. They can be installed using `pip`:

- yfinance
- pandas
- numpy
- matplotlib
