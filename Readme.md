# Time Series Analysis of Electricity Data

This GitHub repository contains a time series analysis of an electricity dataset gathered between September 2010 and February 2021. The dataset comprises 92,016 measurements of electricity-related variables.

## Dataset Information

### Data Source
The dataset is located in the `data` directory. It includes various attributes such as:

- **FullDate**: Date and time in the format yyyy-mm-dd hh:mm:ss.
- **ElecPrice**: Prices of electricity charged in Kw per hour.
- **GasPrice**: Gas price at the time of measurement, as the power was generated from a gas power plant.
- **SysLoad**: Total load on the system or power consumed at each time point.
- **Tmax**: Maximum temperature recorded at each time point.

The description of the dataset can also be found in the `dataset_description.md` file inside the `data` directory.

## Repository Contents

This repository contains the following files:

- `project_notebook.ipynb`: The main Jupyter notebook that performs the time series analysis on the electricity dataset. It includes data preprocessing, exploratory data analysis, forecasting, and visualization of the results.
- `data/dataset_description.md`: A markdown file containing detailed information about the dataset attributes and their meanings.
- `data/electricity_data.csv`: The CSV file containing the raw electricity data.

## Running the Notebook

To run the Jupyter notebook and reproduce the time series analysis, you will need to have Python installed, along with the necessary libraries such as pandas, NumPy, Matplotlib, Prophet, and statsmodels.

Alternatively, you can use an online Jupyter environment or any platform that supports Jupyter notebooks to run the analysis without installing anything locally.