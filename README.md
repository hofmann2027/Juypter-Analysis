# Stock Analysis Dashboard

## Overview
This repository contains a Jupyter Notebook and helper scripts to download stock data, compute metrics (Sharpe, Sortino, Calmar, Beta, etc.), run ARIMA & GARCH forecasts, run Monte Carlo simulations, and display results in a Voila dashboard.

## Requirements
- Python 3.10+ recommended
- See `requirements.txt` for pip install list.

## Quick setup (macOS / Linux)
```bash
# clone
git clone https://github.com/YOUR_USERNAME/stock-analysis-dashboard.git
cd stock-analysis-dashboard

# create venv & activate
python3 -m venv venv
source venv/bin/activate

# install deps
pip install -r requirements.txt

# open in VS Code
code .
