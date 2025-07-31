
# Dissertation_R_codes 

This repository contains the R scripts used in the analysis of my industry project for MSc Actuarial Science. 
This project consists of two research: We first demonstrates the how flood exposure affects financial performance across different supply
chain roles, quantiles, and climate change assumptions by using quantile regression and
Monte Carlo simulation. In parallel, we evaluate time series models (ARIMA, ARIMA-GARCH) and a deep
learning model (LSTM) on their ability to predict UK green bond prices. 

## Repository Structure

- Dissertation_R_codes_1.Rmd: Main script for data loading and complete modelling for quantile regression and Monte Carlo simulation

- Dissertation_R_codes_2.Rmd: Main script for data loading and complete modelling for ARIMA, ARIMA-GARCH, and LSTM models

- csv files: Datasets used in this 

## Dependencies

- R (version ≥ 4.5.0)

- Required packages: quantreg, keras, tensorflow, forecast etc

## How to Run

- Load the dataset into your R environment

- Source the Rmd files

- Output include dataset summaries, model parameters, diagnostic plots, regression coefficients, simulation results. 
   Note that some tabular summaries are stored in variables rather than printed out.