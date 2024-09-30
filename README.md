# Stock market portfolio optimization

![Banner](
This project focuses on optimizing a stock market portfolio using modern portfolio theory. The goal is to find an optimal combination of assets that maximizes returns while minimizing risk, based on historical data.

## Table of Contents
- [Introduction](#introduction)
- [Data Source](#data-source)
- [Project Workflow](#project-workflow)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction
In stock market portfolio optimization, investors aim to select the best possible mix of stocks to maximize returns and minimize risk. This project applies concepts such as the efficient frontier and Sharpe ratio to determine the most favorable allocation of stocks.

## Data Source
The stock data used in this project was obtained through the **Yahoo Finance API**. Historical daily data for selected stocks, including **Adjusted Close, Open, High, Low, Close, and Volume**, was used to calculate returns and risks.

## Project Workflow
1. **Data Collection**: Historical stock price data is fetched for multiple stocks.
2. **Data Preprocessing**: The stock data is cleaned, and daily returns are computed.
3. **Portfolio Simulation**: 
   - Simulate various portfolio combinations of stock allocations.
   - Calculate expected returns, portfolio volatility (risk), and Sharpe ratio for each combination.
4. **Efficient Frontier & Optimization**:
   - Identify the portfolio with the highest Sharpe ratio.
   - Visualize the efficient frontier and optimal portfolio.

## Key Features
- **Risk and Return Calculation**: Calculation of daily returns and standard deviation to quantify risk.
- **Portfolio Optimization**: Optimization using Monte Carlo simulations to find the ideal asset allocation.
- **Efficient Frontier Visualization**: Visual display of the risk-return trade-offs for various portfolios.
- **Sharpe Ratio Maximization**: Identify portfolios with the best risk-adjusted returns.

## Technologies Used
- **Python**
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib & Seaborn**: For data visualization.
- **Yahoo Finance API**: For fetching historical stock data.

## Results
- **Optimal Portfolio**: The portfolio with the highest Sharpe ratio was determined, showing the best balance between risk and return.
- **Efficient Frontier**: A curve representing the optimal portfolios at various levels of risk, allowing investors to choose according to their risk tolerance.
- **Visualization**: Graphs showcasing portfolio performance and the efficient frontier were generated.

## Conclusion
So, this is how stock market portfolio optimization works. Stock market portfolio optimization involves analyzing price trends, calculating expected returns and volatilities, and determining the correlations between different stocks to achieve diversification.

## How to Run
1. Clone this repository:
    ```bash
    git clone https://github.com/heyamay/stock-market-portfolio-optimization.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### 🚀 About Me
#### Hi, I'm Amay Jaiswal! 👋
I am a Data Analytics Enthusiast and  Data science practitioner

[Linkedin](https://www.linkedin.com/in/heyamay/)
