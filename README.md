# Financial Market Forecasting with CNNs and Triple-Barrier Labeling

## Project Overview
This project develops a deep learning framework for financial market forecasting using Convolutional Neural Networks (CNNs) with Triple Barrier labeling. The system evaluates ETF price movements (SPY, IWM, DIA) from 2019-2024, comparing performance against traditional technical strategies.

## Key Features
- **CNN Architecture**: 2D CNN for financial time series pattern recognition as proposed by Omer and Ahmet (2018)
- **Triple-Barrier Labeling**: Adapts López de Prado's method for movement classification
- **Comparative Analysis**: Benchmarks against RSI, MACD, SMA, EMA, and Bollinger Bands

## Results Highlights
| Metric        | SPY    | IWM    | DIA    |
|--------------|--------|--------|--------|
| Best Sharpe   | 1.01   | 0.88   | 1.18   |
| Min Drawdown | -10.3% | -25.5% | -13.3% |
| Annual Return | 12.0%  | 15.5%  | 13.5%  |
