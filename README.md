# Asian Banks Risk Modelling

This repository contains a Python script for calculating and backtesting Value at Risk (VaR) and Conditional Value at Risk (CVaR) for a portfolio of assets using parametric, historical, and Monte Carlo simulation methods.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

This project aims to provide a comprehensive tool for assessing and managing portfolio risk. It implements three widely used VaR models:

- **Parametric VaR:** Assumes that returns follow a normal distribution.
- **Historical VaR:** Uses historical returns to estimate potential losses.
- **Monte Carlo VaR:** Simulates a large number of scenarios to estimate the distribution of potential losses.

In addition to VaR, the script also calculates CVaR (also known as Expected Shortfall), which provides a more conservative measure of risk by considering the average loss in the worst-case scenarios.

## Features

- Calculates VaR and CVaR using three different methods: parametric, historical, and Monte Carlo simulation.
- Backtests the VaR models using traffic light and Kupiec tests.
- Generates visualizations of the portfolio returns and VaR estimates.
- Supports multiple assets and customizable parameters.

## Installation

1. Clone the repository:
2. Install the required libraries

## Usage

1. Update the `tickers`, `start_date`, `end_date`, `confidence_level`, `portfolio_value`, and `days` variables in the script to reflect your portfolio and desired parameters.
2. Run the script
3. The script will output the calculated VaR and CVaR values, backtesting results, and visualizations.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.
