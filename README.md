# Car-Price-Prediction
This Car Price Prediction project leverages machine learning to estimate the selling price of used cars based on various characteristics provided in the dataset. It aims to streamline and enhance the process of vehicle evaluation, helping users make informed decisions when buying or selling cars.

## Key Technologies

**Programming Language:**  
- Python

**Libraries & Frameworks:**  
- `pandas` &ndash; Data handling and preprocessing  
- `scikit-learn` &ndash; Machine learning and model building  
- `XGBoost` &ndash; Advanced ensemble regression model  
- `Jupyter Notebook` &ndash; Interactive analysis, prototyping

**Models Utilized:**  
- Linear Regression (`LR`)  
- Random Forest (`RF`)  
- Gradient Boosting Regressor (`GBR`)  
- XGBoost Regressor (`XG`)

 **GUI Technology:**  
A user-friendly graphical interface (GUI) is implemented, allowing easy input of car details and instant visualization of predicted prices.

## Data Source Information

**Features Included:**  
- `Car_Name`: Name of the car model  
- `Year`: Year of manufacture  
- `Selling_Price`: Price at which the car is being sold  
- `Present_Price`: Current market price of the car  
- `Kms_Driven`: Total kilometers the car has been driven  
- `Fuel_Type`: Type of fuel (Petrol, Diesel, CNG)  
- `Seller_Type`: Seller category (Dealer or Individual)  
- `Transmission`: Transmission type (Manual or Automatic)  
- `Owner`: Number of previous owners  

## Sample Data

| Car_Name | Year | Selling_Price | Present_Price | Kms_Driven | Fuel_Type | Seller_Type | Transmission | Owner |
|----------|------|--------------|---------------|------------|-----------|-------------|--------------|-------|
| ritz     | 2014 | 3.35         | 5.59          | 27000      | Petrol    | Dealer      | Manual       | 0     |
| sx4      | 2013 | 4.75         | 9.54          | 43000      | Diesel    | Dealer      | Manual       | 0     |
| ciaz     | 2017 | 7.25         | 9.85          | 6900       | Petrol    | Dealer      | Manual       | 0     |
| wagon r  | 2011 | 2.85         | 4.15          | 5200       | Petrol    | Dealer      | Manual       | 0     |
| swift    | 2014 | 4.60         | 6.87          | 42450      | Diesel    | Dealer      | Manual       | 0     |

## Features and Highlights

- **GUI:** A simple and intuitive interface for real-time car price prediction. Users enter car features and immediately receive the estimated price.

- **Model Comparison:** Four regression models are benchmarked for prediction accuracy.

- **Feature Engineering:** Includes a derived feature for car age, improving prediction performance.

- **Automatic Encoding:** Categorical variables such as Fuel_Type, Seller_Type, and Transmission are transformed into numeric values for model training.

- **Evaluation Metrics:** R2 scores for each model:
  
  | Model | R2 Score |
  |-------|----------|
  | LR    | 0.679    |
  | RF    | 0.752    |
  | GBR   | 0.868    |
  | XG    | 0.889    |

- **Preprocessing:** Handles missing values, normalizes data, and encodes features for improved model accuracy.

- **User Experience:** The GUI makes the tool accessible and easy to use for non-technical users.

- ## Impact and Insights

- Empowering users with an **interactive tool** (GUI) for accurate and fast car price estimation.

- Dramatic **accuracy improvement** by utilizing ensemble models like XGBoost over basic regression.

- Showcase of practical **feature engineering** and how augmented features (car age) strengthen model performance.

- The modular nature allows **easy deployment and extensibility** for similar regression scenarios in other industries.

- XGBoost’s R2 score of 0.889 suggests strong real-world reliability for the developed pricing tool.

- This repository is a practical resource for data science learners and professionals building regression-based predictive systems with an easy-to-use GUI and robust accuracy.




