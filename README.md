# Optimization & Machine Learning M - Project

Louise CABROLIER  
June 8th 2026

## Project Overview
This project solves a major logistical challenge for **Capital Bikeshare** in Washington D.C.: the asymmetry of traffic flows throughout the day, which causes some stations to become completely empty and others to overflow.

To address this, the project combines two approaches:
1. **Machine Learning:** Building predictive models (Linear Regression and Random Forest) to forecast the hourly bicycle demand (`cnt`) based on historical and weather features.
2. **Operations Research:** Developing a mathematical optimization program with `PuLP` to plan the optimal nightly redistribution of bikes between surplus and deficit stations at the lowest transport cost.

## Repository Content
* `main.ipynb`: The complete Jupyter notebook containing data preprocessing, EDA, ML models, and the final optimization code (fully executed with outputs).
* `main.ipynb - Colab.pdf`: The exported PDF version of the notebook for direct reading.
* `or_data.json`, `about_bike_sharing_dataset.txt`, `bike_sharing_dataset.csv`: documents needed in the ipynb.
