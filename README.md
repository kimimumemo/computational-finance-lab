# Computational Finance Lab

This repository is a collection of my projects in financial mathematics and computational finance. I worked on these during my undergraduate studies in applied mathematics, and the goal was to take core mathematical concepts and apply them to real-world financial problems using Python.

I've grouped the notebooks into topics like option pricing, simulations, portfolio optimization, and risk modeling. The code is all written in Jupyter notebooks and designed to be easy to follow and experiment with.

---

## Project Structure
```
computational-finance-lab/
├── code/
│   ├── options/        # Option pricing models
│   ├── simulation/     # Monte Carlo and stochastic methods
│   ├── risk/           # Value at Risk and risk analysis
│   ├── forecasting/    # Time series forecasting (ARIMA)
│   └── portfolio/      # Portfolio optimization
├── data/               # Stock price datasets used in analysis
├── README.md
└── requirements.txt
```
---

## What's Inside

Here’s a quick overview of what each topic includes:

### Option Pricing
- Binomial model for American and European call options
- Monte Carlo simulations with antithetic variates
- Put option pricing using a mix of Monte Carlo, Binomial CRR, and bBTT methods
- Brownian motion applied to option pricing

### Simulation
- Stochastic simulations, primarily supporting the pricing models

### Risk
- Value at Risk (VaR) analysis using historical simulation methods

### Forecasting
- ARIMA time series forecasting on Apple stock price data

### Portfolio
- Mean-variance portfolio optimization using historical returns