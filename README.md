# README: Analyzing Time Series Data with R

This project demonstrates various analyses and visualizations of time series data using R. The script focuses on exploring and modeling a dataset containing values over time. Below is an overview of the different analyses performed:

## 1. Data Loading and Exploration
- The script reads an Excel file containing time series data using the `readxl` package.
- The dataset is explored to understand its structure and contents.

## 2. Linear Regression
- A linear regression model is fitted to the data to understand the trend over time.
- Summary statistics of the regression model are displayed.
- A line plot is created to visualize the linear trend.

## 3. Residual Analysis
- Residuals of the linear regression model are calculated and plotted to check for randomness and homoscedasticity.

## 4. Q-Q Plot
- A Q-Q plot is created to assess the normality of the residuals.

## 5. Trend Line Visualization
- The actual data and the regression trend line are plotted together to visualize the trend over time.

## 6. Recursive CUSUM Analysis
- Recursive CUSUM analysis is performed to detect shifts in the data over time.
- 95% confidence bands are plotted around the CUSUM line.

## 7. Dynamic Model vs. Actual Data
- Two models are compared: a static model and a dynamic model (random walk).
- The actual data and the random walk model are plotted to compare their trends.

## 8. Particle Filter Test
- A particle filter is applied to the time series data to estimate the underlying process.
- The filtered means and confidence intervals are plotted along with the observed data.

## Usage Instructions:

1. Ensure that R and RStudio are installed on your system.
2. Install the required packages mentioned in the script.
3. Execute the R script to perform the analyses and generate visualizations.
4. Review the results and interpretations provided in the script.

## File Description:

- **NAP.xlsx**: Excel file containing the time series data.
- **script.R**: R script containing the code for data analysis and visualization.

## Credits:

This project was created by Furkan Ozdemir and Izzed Dabbagh as part of Advanced Time Series Analysis. Special thanks to the creators of the R packages used in this script for their contributions to the R community.

