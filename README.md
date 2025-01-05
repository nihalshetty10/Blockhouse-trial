# Blockhouse-trial
# Description
This project explores the impact of Order Flow Imbalance (OFI) on price movements in equity markets, with a focus on both self-impact and cross-impact effects in a multi-asset setting. The key objectives include:

OFI Calculation: Compute OFI at multiple levels of the limit order book (LOB) and aggregate them using Principal Component Analysis (PCA).
Cross-Impact Analysis: Use regression models to quantify the influence of cross-asset OFIs on stock returns.
Predictive Modeling: Assess the short-term predictability of returns based on cross-impact terms.
Visualization: Generate insights using correlation heatmaps, regression results, and cross-impact coefficient networks.

# Findings
Integrated OFIs: Combining multi-level OFIs using PCA significantly enhances the explanatory power of regression models, explaining up to 87% of contemporaneous return variance.
Cross-Impact Terms: Cross-impact coefficients improve the short-term predictability of returns, particularly for 1-5 minute horizons, with a modest but significant R² gain.
Sector-Level Insights: Correlation and network analysis reveal strong cross-asset relationships within sectors, such as Information Technology and Communication Services.
