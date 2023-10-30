# Real-Time Solar Energy Forecasting

## Description

This Project contains a machine learning model aimed at forecasting solar energy generation in real-time. The primary focus is on the region of South Spain, and the model aims to assist the Solar Grid Operator in balancing energy supply and demand efficiently.

## Objective

The primary objective is to:

- Develop a machine learning model that can accurately predict solar energy generation for the next 30 minutes to a few hours.

## Data

The dataset used for this project contains hourly solar radiation data from January 1, 2005, to December 31, 2020. It includes features such as beam (direct) irradiance, diffuse irradiance, reflected irradiance, and other weather-related variables.

- **Source**: PVGIS-SARAH2
- **Location**: South Spain
- **Time Interval**: Hourly

## Methodology

The following steps outline the methodology:

1. **Data Preprocessing**: Handling missing values, outliers, and feature scaling.
2. **Feature Engineering**: Extracting useful features for modeling.
3. **Modeling**: Utilizing Random Forest Regressor for the base model.
4. **Hyperparameter Tuning**: Employing Grid Search and Bayesian Optimization.
5. **Evaluation**: Using RMSE and \( R^2 \) metrics for performance evaluation.

## Results

The optimized Random Forest model achieved the following performance metrics on the test set:

- **RMSE**: \(4.044\) W
- **\( R^2 \)**: \(0.9998\)

## Usage

To run the code, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies.
3. Run the Jupyter notebooks or Python scripts.

## Dependencies

- Python 3.x
- scikit-learn
- Pandas
- NumPy
- Matplotlib
- BayesianOptimization

## Contributors

- [Your Name](https://github.com/your-github-profile)
  
For collaboration or any questions, please feel free to [contact](mailto:your-email@example.com).

## License

This project is licensed under the Apache License - see the [LICENSE.md](LICENSE.md) file for details.
