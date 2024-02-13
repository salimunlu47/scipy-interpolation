# Temperature and Humidity Spline Interpolation

## Overview
This work demonstrates the application of spline interpolation on real-world data to estimate the missing values of temperature and humidity throughout a day. By using the `CubicSpline` function from SciPy's `interpolate` module, we can create a smoother transition between the data points and obtain a more realistic continuous curve that represents the data trends accurately.

## Data
The dataset consists of temperature and humidity measurements taken at specific hours throughout a single day. The temperature is measured in degrees Celsius, and humidity is given as a percentage. The data points are simulated for the purpose of this demonstration.

## Methodology
The data is interpolated using a cubic spline, which is a type of spline built of piecewise third-order polynomials. This method is particularly well-suited for smoothly connecting data points without assuming a single global model, which makes it flexible and adaptive to local variations in the data.

## Files
- `Temperature_Humidity_Interpolation.ipynb`: Jupyter Notebook containing the interpolation analysis.

## Results
The interpolation results are visualized in two graphs. One graph displays the temperature against the hours of the day, and the other displays the humidity against the hours of the day. The blue dots represent the original data points, and the orange line represents the interpolated values, showing the temperature increase until the mid-afternoon and decrease towards the evening, and the inverse pattern for humidity.

## Installation
To run this project, you will need Python and the following libraries:
- NumPy
- SciPy
- Matplotlib

## Usage
To execute the analysis, run the `Temperature_Humidity_Interpolation.ipynb` notebook in a Jupyter environment. The notebook includes comments and markdown cells that guide you through the process.

## Contribution
Contributions to this project are welcome. You can improve the current interpolation, add new datasets, or suggest a new feature. Please submit a pull request or open an issue if you have any feedback.
