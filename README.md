# Irish Wheat Agriculture Analytics

This project explores wheat agriculture in Ireland using public agricultural datasets, statistical analysis, machine learning, sentiment analysis, forecasting, and an interactive Streamlit dashboard.

## Project Overview

The aim of this project was to analyse Irish wheat production and compare it with wider European and global agricultural trends. The analysis focuses on wheat yield, production, farm costs, regional patterns, and farmer sentiment from online agricultural discussion data.

The project combines structured agricultural datasets with unstructured forum text to create a practical analytics workflow, from data acquisition and cleaning through to modelling and dashboard delivery.

## Key Features

- Cleaned and combined agricultural datasets from CSO, FAOSTAT, FADN, and forum data
- Analysed Irish wheat trends by yield, production, region, crop type, and cost
- Compared Ireland with France and the UK using statistical testing
- Applied machine learning models including regression, clustering, and time series forecasting
- Performed sentiment analysis on farming forum discussions using NLP techniques
- Built an interactive Streamlit dashboard for exploring wheat trends and forecasts

## Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Statsmodels
- Plotly
- Streamlit
- BeautifulSoup
- TextBlob / VADER
- Jupyter Notebook

## Analysis Summary

The project began with data acquisition and preparation from multiple agricultural sources. The datasets were cleaned, reshaped, merged, and checked for missing values, outliers, distribution patterns, and suitability for statistical and machine learning analysis.

Exploratory data analysis was used to identify trends in Irish wheat yield, production, regional wheat farming, and cost changes over time. Statistical testing was then used to compare Ireland with France and the UK, including checks for normality, variance, and independence before selecting appropriate parametric or non-parametric tests.

Machine learning methods were applied to explore both prediction and pattern discovery. These included K-Means clustering for global wheat patterns, regression models for agricultural cost prediction, and ARIMA-based time series forecasting for wheat-related trends.

A separate NLP workflow was used to analyse farmer sentiment from online agricultural forum posts. This included text cleaning, tokenisation, feature engineering, sentiment scoring, and comparison of lexicon-based and supervised approaches.

## Dashboard

The Streamlit dashboard presents the main findings in an interactive format. Users can explore:

- Irish wheat forecast trends
- Cost fluctuations in wheat farming
- Wheat farming area by Irish region
- Wheat types over time
- Worldwide wheat production, yield, and clustering
- Country-level comparisons between Ireland, France, and the UK

The dashboard was designed with clarity and practical use in mind, using interactive filters, line charts, and choropleth maps to make the analysis easier to explore.

## Key Outcomes

- Ireland, France, and the UK showed meaningful differences in wheat yield, energy costs, and fertiliser costs.
- Winter wheat represented a major share of Irish wheat production.
- Forecasting models were useful for trend exploration, but prediction accuracy was limited by small dataset sizes.
- Sentiment analysis showed the difficulty of classifying nuanced agricultural discussion, especially where posts were neutral or context-dependent.
- The dashboard translated the analysis into a practical tool for non-technical users.

## Limitations

Some machine learning models were limited by small sample sizes, weak feature relationships, and noisy real-world agricultural data. Rather than forcing high-performing models, the project evaluates model suitability honestly and highlights where additional data would improve predictive performance.

## What I Demonstrated

This project demonstrates my ability to:

- Work with messy real-world datasets from multiple sources
- Clean, reshape, merge, and prepare data for analysis
- Apply statistical testing with appropriate assumption checks
- Build and evaluate machine learning models
- Analyse unstructured text data using NLP
- Communicate results through clear visualisations and an interactive dashboard
- Explain limitations and make evidence-based modelling decisions
