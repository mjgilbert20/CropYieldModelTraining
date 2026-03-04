# CropYieldModelTraining

Created for a hackathon sponsored by Databricks to support their client Corteva with crop yield predictions.

## Hackathon Objective

**Predict-the-Future: 60- and 90-Day Forecast Yield Simulation**

### The Challenge

Students receive a dataset that includes:
- Historical crop yields
- Historical daily/weekly weather
- A 60- and 90-day weather forecast dataset

The challenge is to:
1. Build a predictive model that estimates expected yield for the current growing season based on near-term forecast weather
2. Quantify uncertainty (e.g., "yield could drop 10-18% if rainfall is below X")
3. Provide early-warning insights for agronomists or growers

### Expected Outcomes

- A yield prediction engine that updates automatically when new forecasts arrive
- Scenario runs demonstrating:
  - "Dry next 60 days"
  - "Excessive rainfall in next 90 days"
  - "Heatwave probability increases > 25%"

### Bonus Objectives

- Visualize prediction intervals and uncertainty bands
- Provide a simple Natural Language summary for farmers (e.g., "If temperatures exceed 95F for more than 4 days expect yield decreases by 12%.")

## Notebooks

This project includes the following Jupyter notebooks:

- **Crop Yield Model Training.ipynb** - Train and develop the crop yield prediction models
- **view predictions.ipynb** - View and analyze predictions from the trained model

## Data Sources

This project uses data from the following sources:

- **NOAA Daily Weather Observations** - Available from the [Databricks Marketplace](https://marketplace.databricks.com/). This large-scale dataset provides comprehensive historical weather data to train and validate the yield prediction models.
- **Crop Yield History** - Historical yield data from [Corteva RMA County Yields](https://github.com/elisemoe/Corteva-RMA-County-Yields)
