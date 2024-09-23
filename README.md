# Stock Market Prediction System

This repository contains the implementation of the paper *"An Intelligent Technique for Stock Market Prediction"* by Mohammad Mekayel Anik, Mohammad Shamsul Arefin, and M. Ali Akber Dewan. The system uses historical data from the Dhaka Stock Exchange (DSE) and Chittagong Stock Exchange (CSE) to predict stock prices using machine learning techniques, primarily focusing on linear regression.

## Table of Contents
- [Introduction](#introduction)
- [System Architecture](#system-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Modules](#modules)
- [Experimental Results](#experimental-results)
- [Contributors](#contributors)
- [License](#license)

## Introduction

The stock market prediction system is designed to assist investors in making informed decisions by predicting future stock prices based on historical data. The system scrapes data from stock market websites, preprocesses it, and applies machine learning models to make predictions.

### Key Features:
- Scrapes real-time data from DSE and CSE.
- Predicts stock prices using linear regression.
- User-friendly interface for querying stock prices.
- Supports dynamic input of stock symbols and prediction queries.

## System Architecture

The system is composed of three main modules:
1. **Data Preprocessing**: Scrapes data from DSE and CSE websites using `BeautifulSoup`, and stores it in a database for further analysis.
2. **Prediction**: A linear regression model is used to predict stock prices based on the historical data stored in the database.
