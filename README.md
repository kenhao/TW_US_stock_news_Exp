# Exploring the Predictability of Taiwanese News on Stock Prices and the Causal Relationship between the Taiwan Weighted Index and the U.S. NASDAQ Index

## Introduction

This project explores the predictability of Taiwanese news on stock prices and the causal relationship between the Taiwan Stock Exchange Capitalization Weighted Stock Index (TAIEX) and U.S. stock markets. The study incorporates a mixed analysis approach, using Taiwanese stock prices and financial news headlines, along with U.S. stock prices as model inputs. It employs Pearson correlation analysis and Granger causality tests to analyze the relationships.

## Methodology Overview
- Data Preparation: Collected financial news headlines from Taiwan and stock price data from Taiwan and the U.S.
- Model Building: Employed Long Short-Term Memory (LSTM) networks for combined data of time series data and news text.
- Correlation Analysis: Analyzed the correlation between Taiwanese and U.S. stock prices using Pearson's correlation coefficient.
- Causality Testing: Applied Granger causality tests to investigate the causal relationships between the Taiwanese and U.S. stock markets.


## Experiment Design
**The research is structured into three experiments**:
- **Experiment 1**:
Uses Taiwanese financial news headlines and TAIEX prices as inputs to the model.
- **Experiment 2**
Incorporates NASDAQ as a third input based on its high correlation with TAIEX.
- **Experiment 3**:
Executes Granger causality tests between TAIEX and NASDAQ to determine causal relationships.
![IMBOOKSTORE Screenshot](https://i.imgur.com/hIjGRUQ.jpg)



## Experiment result
The results demonstrate that U.S. stock markets, particularly NASDAQ, significantly influence the Taiwanese market. However, this conclusion is limited to short-term relations, and further study is needed for long-term implications.



