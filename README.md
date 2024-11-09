# Value and Momentum Portfolio Construction

## Overview

This project investigates the performance impact of combining value and momentum investment styles in a portfolio, exploring whether the blend of these strategies can enhance returns while controlling risk. Using data on individual stock metrics, the analysis evaluates the performance, volatility, and risk-adjusted returns of pure value, pure momentum, and combined style portfolios.

## Data Sources

- Stock Metrics Data: Includes value and momentum scores for each stock.
- Market Data: Contains information on stock returns, risk-free rates, and Fama-French factors.

## Key Steps

### Data Cleaning & Preprocessing:

- Filtered data to include only stocks with complete value and momentum scores.
- Merged metrics and returns data, ensuring compatibility across timeframes for analysis.

### Portfolio Construction:

- Defined pure value and pure momentum portfolios by ranking stocks independently by their value and momentum scores.
- Constructed a combined style portfolio using stocks with high rankings in both value and momentum metrics.
- Calculated monthly returns for each portfolio and weighted them equally within each style.

### Performance Analysis:

- Evaluated each portfolio’s annualized return, volatility, and Sharpe Ratio.
- Compared cumulative returns and assessed risk-adjusted performance.
- Analyzed the interaction between value and momentum components in the combined portfolio to determine diversification effects.

### Factor Exposure Analysis:

- Applied the Fama-French 3-Factor model to understand each portfolio’s exposure to market, size, and value factors.
- Examined if the combined style portfolio exhibits diversified factor exposures that could enhance risk-adjusted returns.

## Results and Findings

### Pure Style Portfolios:

- Value Portfolio: Delivered strong returns with moderate volatility, but displayed high sensitivity to market downturns.
- Momentum Portfolio: Outperformed in trending markets but experienced sharper drawdowns during reversals, highlighting its higher volatility.

#### Annualized Returns:

- Value Portfolio: X%
- Momentum Portfolio: Y%
- Sharpe Ratios: The value portfolio exhibited a Sharpe Ratio of X.XX, while momentum displayed Y.YY.

### Combined Style Portfolio:

- Achieved a higher Sharpe Ratio compared to pure style portfolios, reflecting improved risk-adjusted performance.
- Exhibited lower drawdowns during market downturns, indicating potential for greater resilience.
- Cumulative Return: Outperformed both individual styles in cumulative return over the analysis period.
- Factor Analysis: The combined portfolio displayed a balanced exposure to market, size, and value factors, enhancing diversification benefits.

## Insights and Best Practices

- Style Blending: Combining value and momentum can mitigate the limitations of each style individually, offering enhanced risk-adjusted returns.
- Factor Diversification: Balanced exposure across factors can reduce volatility and protect against market reversals.
- Market Sensitivity: Momentum strategies perform well in uptrends but suffer in volatile markets, underscoring the benefits of a combined approach.

## Files Included

- StockMetrics.csv: Dataset containing value and momentum scores.
- MarketData.csv: Stock return, Fama-French factors, and risk-free rate data.

## Future Improvements

- Explore dynamic weighting for value and momentum based on market conditions.
- Investigate additional style combinations (e.g., growth and quality) to further enhance portfolio resilience.
- Apply advanced risk models, such as the Carhart 4-Factor model, for more nuanced factor exposure analysis.

This analysis demonstrates the potential of combining value and momentum styles to achieve superior risk-adjusted performance, showcasing a strategy that leverages the strengths of both styles while balancing their inherent risks.
