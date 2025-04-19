# Rohit-Sharma-ODI-Analysis-and-2027-World-Cup-Prediction
Analyze Cricketer Rohit Sharma's ODI match stats and predict his chances of getting selected f0r the 2027 world cup
# Rohit Sharma ODI Performance Analysis

This project analyzes the ODI performance of Rohit Sharma, the Indian cricketer. It uses data from his ODI matches to explore his performance trends, identify key performance indicators, and predict the probability of him playing in the next ODI World Cup.

## Project Structure

- `rohitsharmaodi (2).xlsx`: The dataset containing Rohit Sharma's ODI match data.
- `Rohit_Sharma_ODI_Analysis.ipynb`: The Jupyter Notebook containing the data analysis, visualization, and prediction code.

## Data Analysis

The project performs the following data analysis steps:

- **Data Loading:** Reads the data from the Excel file into a pandas DataFrame.
- **Data Exploration:** Examines the dataset's characteristics, including shape, data types, missing values, and distributions.
- **Data Wrangling:** Cleans the data, handles missing values, engineers new features (rolling averages, batting average, opponent-specific performance), and extracts date components.
- **Data Analysis:** Analyzes performance trends over time, calculates key statistics (average runs, strike rate, century frequency), and investigates correlations between performance metrics.
- **Data Visualization:** Creates various visualizations, including line plots for performance over time, histograms for data distributions, bar charts for opponent and venue performance, and a heatmap for correlation analysis.

## Prediction

The project attempts to predict the probability of Rohit Sharma playing in the next ODI World Cup using a RandomForestClassifier model. However, due to severe class imbalance in the training data (almost no instances of Rohit Sharma being selected for the World Cup), the model's performance is limited. The prediction part requires further improvement with more data and model adjustments.

## Usage

1. Open the `Rohit_Sharma_ODI_Analysis.ipynb` notebook in Google Colab.
2. Make sure you have the `rohitsharmaodi (2).xlsx` file in the same directory as the notebook.
3. Run the notebook cells sequentially to execute the code.

## Dependencies

- Python 3.x
- pandas
- NumPy
- scikit-learn
- matplotlib
- seaborn
- imblearn

You can install these dependencies using `pip`:
