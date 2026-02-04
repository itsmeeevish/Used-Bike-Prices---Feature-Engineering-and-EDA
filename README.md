# Used Bike Prices - Feature Engineering and EDA

## Project Overview
This project analyzes used bike prices in India using machine learning techniques. The goal is to predict bike prices based on features like brand, model year, kilometers driven, mileage, power, etc.

## Dataset
The dataset contains information about used bikes including:
- model_name: Name of the bike model
- model_year: Manufacturing year
- kms_driven: Kilometers driven
- owner: Owner type (first, second, etc.)
- location: Seller location
- mileage: Fuel efficiency (kmpl)
- power: Power in BHP
- price: Selling price (target variable)

## Project Structure
1. **Data Collection & Preparation**: Loading and initial data inspection
2. **Exploratory Data Analysis**: Understanding data distributions and relationships
3. **Feature Engineering**: Creating new features and handling categorical variables
4. **Model Building**: Training and evaluating machine learning models

## How to Run
1. Install requirements: `pip install -r requirements.txt`
2. Place dataset in `data/bikes.csv`
3. Run Jupyter notebooks in sequence or execute `main.py`

## Key Features
- Comprehensive data cleaning and preprocessing
- Feature extraction from model names
- Multiple visualization techniques
- Various ML models for price prediction
- Hyperparameter tuning
