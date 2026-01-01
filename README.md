📊 Trader Performance vs Market Sentiment Analysis
📌 Project Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed) and trader performance using historical trading data from Hyperliquid.
The goal is to uncover behavioral patterns, evaluate performance under different sentiment regimes, and extract actionable insights that can inform smarter trading strategies.

🎯 Objectives

Explore how market sentiment influences trader behavior

Analyze performance metrics under Fear vs Greed conditions

Identify hidden patterns such as overtrading, risk amplification, and discipline

Provide data-driven insights to improve trading decisions

📂 Datasets Used

1. Bitcoin Market Sentiment Dataset

Source: Fear & Greed Index
Key Columns:

sentiment_date – Date of sentiment

classification – Market sentiment (Fear or Greed)

2. Hyperliquid Historical Trader Data

Key Columns:

account – Trader identifier

coin – Trading asset

execution_price

size_tokens, size_usd

side, direction

timestamp_ist

closed_pnl

fee

Other trade metadata

🛠️ Tools & Technologies

Python

Pandas – Data manipulation

NumPy – Numerical analysis

Matplotlib & Seaborn – Visualization

Jupyter Notebook – Interactive analysis

🔄 Data Preprocessing

Standardized column names and data types

Converted timestamps to datetime (IST-aligned)

Removed invalid and zero-size trades

Cleaned and normalized sentiment labels

Merged sentiment data with trading data using trade dates

📈 Feature Engineering

Key performance-oriented features were created:

is_profitable – Win/Loss indicator

net_pnl – Fee-adjusted PnL

pnl_per_usd – Risk-adjusted efficiency

Trade frequency and trade size metrics

📊 Analysis Performed

Sentiment-wise performance comparison

Win rate, average PnL, and trade size analysis

Distribution analysis of profits and losses

Account-level sentiment sensitivity evaluation

Behavioral pattern detection (overtrading, risk amplification)

🔍 Key Insights

Trader performance varies significantly across Fear and Greed regimes

Greed periods show higher activity but lower risk-adjusted returns

Fear periods favor disciplined and selective trading

Overtrading and excessive risk-taking are more common during Greed

Consistently profitable traders remain sentiment-agnostic

📌 Strategy Recommendations

Reduce leverage and trade frequency during Greed phases

Focus on net and risk-adjusted PnL rather than win rate alone

Apply contrarian or mean-reversion strategies during Fear

Track personal performance across sentiment regimes

⚠️ Limitations

Sentiment data is available at a daily granularity

Analysis is observational, not predictive

Intraday sentiment shifts are not captured

🔮 Future Enhancements

Predictive modeling using sentiment as an input feature

Trader clustering based on sentiment sensitivity

Intraday sentiment integration

Strategy backtesting under sentiment-aware rules

✅ Conclusion

This analysis demonstrates that market sentiment strongly influences trader behavior and performance. Traders who maintain discipline and control risk—especially during Greed phases—achieve more consistent results. Incorporating sentiment awareness can significantly enhance trading strategies and decision-making.
