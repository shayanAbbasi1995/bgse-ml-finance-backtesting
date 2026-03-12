# BGSE ML for Finance — Back-testing Trading Strategies

R Markdown assignment from the Machine Learning for Finance course at the Barcelona School of Economics (BGSE).

## Contents

`HW02.Rmd` implements a quantitative trading pipeline including:

- **Data collection** — AMZN price data and sentiment indicators (positive, negative, certainty, uncertainty, financial up/down scores)
- **Portfolio optimization** — mean-variance optimization using `PortfolioAnalytics` and `fPortfolio`
- **Back-testing** — evaluating strategy performance over a 2018–2019 out-of-sample period
- **Sentiment-based signals** — constructing bull/bear composite sentiment indices from textual scores

## Dependencies (R)

`lpSolve`, `fPortfolio`, `PortfolioAnalytics`, `GenSA`, `DEoptim`, `quantmod`, `PerformanceAnalytics`, `xts`, `zoo`, `matrixStats`, `doParallel`
