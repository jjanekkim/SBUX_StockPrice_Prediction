# Starbucks Stock Price Prediction - Time Series

## Overview
This project focuses on conducting time series analysis utilizing the ARIMA (AutoRegressive Integrated Moving Average) model to build a predictive model for stock prices. It encompasses various stages including Exploratory Data Analysis (EDA), model training, and subsequent testing for validation.

# Table of Contents
* [Introduction](#introduction)
* [General Info](#general-info)
* [Dependencies](#dependencies)
* [Project Structure](#project-structure)

## Introduction

This project is dedicated to constructing a stock price prediction model—a challenging task due to the multifaceted influences impacting stock prices. The focus here is on developing a short-term prediction model utilizing the ARIMA (AutoRegressive Integrated Moving Average) technique.

## General Info

In this project, I utilized the free Yahoo Finance API to collect historical stock price data for Starbucks. Focusing on a three-month window, I delved into the dataset and discovered a significant surge in stock prices during early November 2023. This surge coincided with Starbucks reporting a considerable revenue increase. However, the stock price gradually declined from mid-November onwards.

To assess the dataset's stationarity, I employed the Dickey-Fuller Test. Additionally, I used autocorrelation (AR/p) and partial autocorrelation (MA/q) to narrow down the parameter range for the ARIMA model. The Root Mean Squared Error (RMSE) for the optimal model was calculated at 0.84 cents.

## Dependencies
This project is created with:
- Python version: 3.11.3
- Pandas version: 2.0.1
- Numpy version: 1.24.3
- Matplotlib package version: 3.7.1
- Seaborn package version: 0.12.2
- statsmodel module version: 0.14.0
- yahoofinance module version: 0.2.31

## Project Structure
- **Data**: The data utilized in this project was collected using the Python module for the Yahoo Finance API.
- **EDA_ModelTrain**: This Jupyter Notebook file encompasses both exploratory data analysis and model training stages.
- **ModelTest**: This Jupyter Notebook file includes the testing of the ARIMA model and showcases its corresponding results.
