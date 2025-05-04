# House Price Prediction Machine Learning Model

## 1. Project Overview
This project aids in accurately predicting the house prices for houses within the Bengaluru area. The price of each house is based on various features like area type, size, and total square footage of houses.
It involves data cleaning, feature engineering, and a choosing the best price prediction model. The dataset contains multiple attributes and is obtaind from [Kaggle - Bengaluru House Data](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)

## 2. Features
- **Data Cleaning and Processing**  
  Apply data manipulation techniques to create derived features and create a pipline that Processes, Prepares and Cleans the data making it suitable for the predictive model.    

- **Predictive Model**  
  Uses GridSearchCV and varying Hyperparameters to determine the best price prediction model that accurately predicts house prices based on features.

## 3. Installation

To run the project locally, follow these steps:

  1. Download the `House_Price_Prediction.ipynb` file.
  2. Ensure you have Jupyter Notebook installed on your device.
  3. Install the required libraries:
     ```bash
     pip install pandas numpy plotly.express matplotlib.pyplot collections regex sklearn plotly.graph_objects pandas numpy seaborn
  4. Open the notebook using Jypyter Notebook.

## 4. Files Included

### 1. `House_Price_Prediction.ipynb`
  - Download the dataset from the Data Sources 'https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data'.
  - Performs initial Data Exploration, Analytics. Further grouping, aggregating, combining processing and preparing the data.
  - Performs Predection of house prices bu choosing the best predective model from available options via hyperparameter tuning through GridSearchCV
  - Libraries used in this notebook: pandas, numpy, plotly.express, matplotlib.pyplot, collections, regex, sklearn, seaborn.

## 5. Data Sources

### Source 1: 'https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data/'
A kaggle website containing the data on the Number of Bedrooms, Number of Balconies, House Size, Price, etc. within the Bengaluru area. 

1. **Bengaluru_House_Data.csv**  
   House information: Area type,	Availability,	Location	Size	Society	Total sqft,	Bath,	Balcony,	Price.

## 6. Libraries Used

This project uses the following Python libraries:

1. **pandas** – For data manipulation and cleaning.  
2. **numpy** – For numerical operations and transformations.  
3. **plotly.express** – For creating interactive visualizations with Plotly.
4. **matplotlib.pyplot** - For creating visualizations.
5. **seaborn** – Visualising the confusion matrix to aid in determining model performance.
6. **collections** – Grouping and Counting classes for each feature.
7. **regex** - Aids in feature cleaning and preparation
8. **sklearn** - For splitting the data appropriately for testing, training, building and determining the best predective model, price prediction. 

## 5. How to Use

### Running the Notebooks:

1. **Data Cleaning, Model Building and Prediction**:
   - Open `House_Price_Prediction.ipynb` in Jupyter Notebook.
   - Follow the steps to extract, clean, transform the data, build the model, evaluate the model and predict.
   - Evaluate the output.

## 6. License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
