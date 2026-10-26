# data_anlyst-one-
THIS IS PROJECT OF DATA ANLYST .
# Airline Passenger Satisfaction Analysis

This project explores airline passenger data to understand passenger characteristics, travel patterns, service ratings, and satisfaction.

## Project Overview

The notebook uses Python and data visualization to examine the airline passenger satisfaction dataset. It creates charts to compare passenger groups and explore how age, travel class, flight distance, and service ratings relate to satisfaction.

## Dataset

The notebook loads the file:

```text
airline_passenger_satisfaction.csv
```

Place this CSV file in the same folder as the notebook before running it.

## Analysis Included

- Dataset structure and basic information
- Gender and customer-type counts
- Passenger age distribution
- Departure and arrival time convenience
- Type of travel and travel class distributions
- Age distribution by passenger satisfaction
- In-flight entertainment and baggage-handling ratings
- Average cleanliness, food and drink, and in-flight service ratings by age
- Relationship between age and flight distance

## Libraries Used

- **Pandas** — loading and analyzing the dataset
- **NumPy** — numerical operations
- **Matplotlib** — charts and visualizations
- **Seaborn** — statistical plots

## Installation

Install the required libraries:

```bash
python -m pip install pandas numpy matplotlib seaborn notebook
```

## How to Run

1. Download or clone the repository.
2. Place `airline_passenger_satisfaction.csv` in the project folder.
3. Install the libraries listed above.
4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the notebook and run the cells in order.

## Purpose

This is an exploratory data analysis (EDA) project intended to practice data inspection, grouping, and visualization. The charts help explore patterns in the dataset; they do not by themselves prove that one factor causes passenger satisfaction.

## Note

The notebook expects the CSV file to exist at the path used in `pd.read_csv()`. Make sure the dataset is included in your repository or provide clear instructions for obtaining it.
