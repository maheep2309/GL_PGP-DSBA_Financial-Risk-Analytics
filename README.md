# GL_PGP-DSBA_Financial-Risk-Analytics
This project builds a financial risk analytics solution by analyzing company balance-sheet metrics and stock-market behaviour. It applies EDA, risk modelling, and machine-learning techniques to predict corporate default likelihood and evaluate market volatility, helping investors make data-driven, proactive decisions.

# Project Summary
Part A: Corporate Default Prediction (Machine Learning):

Using 52 financial variables from company balance sheets, the project builds a Financial Health Assessment Tool to predict whether a company’s net worth will become negative next year. Exploratory analysis reveals significant variability in profitability, liquidity, leverage, turnover ratios, and working-capital health across companies. Defaulters exhibit lower profits, weaker liquidity, higher leverage, poor reserves, smaller asset bases, and weaker operational margins.
The data undergoes cleaning, missing-value treatment with KNNImputer, outlier assessment, scaling, and SMOTE oversampling to address 21% default imbalance. Multiple models are developed: Logistic Regression, Tuned Logistic Regression, Random Forest, and Tuned Random Forest. After addressing multicollinearity, hyperparameter tuning, and threshold optimization, the Tuned Random Forest emerges as the best model with Recall ≈ 63%, offering strong default detection critical for financial risk mitigation. Key predictors include PAT ratios, debt-to-equity, solvency ratios, working capital, and P/E signals. Actionable recommendations include monitoring leverage, enforcing liquidity thresholds, tracking profitability, and implementing early-warning scorecards.

Part B: Market Risk Analysis (Python-Based Time-Series Risk Study):

This section evaluates market-level risk by analysing 8 years of weekly stock prices for five major Indian companies: ITC, Bharti Airtel, Tata Motors, DLF, and Yes Bank. Time-series scatterplots reveal distinctive patterns—Airtel and DLF show strong long-term uptrends, ITC exhibits a stable but recently bullish movement, Tata Motors reflects cyclical behaviour, and Yes Bank shows severe decline and stagnation post-crisis.
Log returns are computed to study risk-adjusted performance. Mean–volatility analysis reveals ITC as a low-risk stable asset, Airtel and DLF as strong return-generating options with moderate risk, and Tata Motors as high-volatility cyclical. Yes Bank shows the worst profile with negative returns and high volatility. These insights support portfolio construction strategies such as combining low-risk stabilizers (ITC) with high-growth picks (DLF/Airtel) while avoiding distressed assets like Yes Bank.

Overall Impact:

Together, the two components offer an integrated financial-risk framework that:
Predicts company-level default risk using ML techniques.
Evaluates market volatility and stock-level risk–return behaviour.
Identifies core financial indicators driving distress.
Helps investors design diversified, risk-aware portfolios.
Supports proactive risk mitigation and strategic financial decision-making.
