![header](https://i.ibb.co/kHXgpXS/Bitcoin-Banner-1900-x-500.jpg)

# Cryptocurrency Time Series
Authors: [TJ Bray](https://www.linkedin.com/in/thomas-tj-bray-24499354/), [Aalok Joshi](https://www.linkedin.com/in/aalokjoshi113/), [Paul Lindquist](https://www.linkedin.com/in/paul-lindquist/)

## Overview
Time series is, quite simply, a series of data points indexed over time. Time series analysis is used to extract meaningful statistics, patterns, etc. from time series data, while time series forecasting uses a model to predict future values based on previously observed data. We encounter time series in our everyday lives in the form of outside temperatures, home values and stock prices, all over time.

Stock price forecasting has generally limited success, as factors like purchase volume and current events can cause price fluctuations. Can the same be said of cryptocurrency, namely the heavily traded Bitcoin? In this project, we use traditional time series analysis and forecasting to predict Bitcoin prices.

We choose Bitcoin for 2 reasons:
- Greatest gross price
- Trading popularity (volume)

## Business Objective
This project postulates that we are cryptocurrency traders speaking to our stakeholders, Future Crypto Investors of America, a group of young, future investors. We briefly outline our process for selecting the best performing model and quickly jump into the results. We give particular focus to comparing predicted vs. actual prices using past data and provide accompanying visualizations. We expect this to both highlight performance and encourage future investment.

We take a daily, predictive approach to forecast if the Bitcoin price will increase, decrease or stay flat. We then subsequently provide guidance to buy, sell or hold that day.

## Data
This project uses [datasets](https://www.kaggle.com/yamqwe/cryptocurrency-extra-data-bitcoin) from Kaggle user [Yam Peleg](https://www.kaggle.com/yamqwe) created for the ***[G-Research Crypto Forecasting](https://www.kaggle.com/c/g-research-crypto-forecasting)*** competition.

## Methodology
We employ time series analysis and predictive modeling for the forecasting.

## Results
TBD

## Conclusions
TBD

For next steps, we would like to explore the following:
- Time series analysis and forecasting for Ether (the 2nd largest cryptocurrency commonly known as Ethereum)
- A time-intensive and computationally expensive, iterative, predictive modeling approach to Bitcoin price using various sliding windows
- Compare the time series modeling approach to other machine learning algorithms (random forest, XGBoost, etc.)
- Develop a trading strategy to maximize returns

## For More Information
Please review our full analysis in our [Jupyter Notebook](MAIN_Notebook.ipynb) or [presentation deck](Project_Presentation.pdf).

For additional questions, please contact [TJ](https://www.linkedin.com/in/thomas-tj-bray-24499354/), [Aalok](https://www.linkedin.com/in/aalokjoshi113/), [Paul](https://www.linkedin.com/in/paul-lindquist/).

## Respository Structure
```
├── data                                <- Cleaned, exported .csv files to import in MAIN Notebook
├── README.md                           <- The top-level README for reviewers of this project
├── MAIN_Notebook.ipynb                 <- Narrative documentation of analysis in Jupyter Notebook
└── Project_Presentation.pdf            <- PDF version of project presentation
```
