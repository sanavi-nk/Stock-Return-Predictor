# Stock-Return-Predictor
Pull historical price data, engineer features (moving averages, lagged returns, RSI, rolling volatility), and train a Random Forest to predict next-day returns. Use a time-series train/test split (no shuffling), then backtest a long/short strategy against buy-and-hold and evaluate it with Monte Carlo resampling instead of a single equity curve.
