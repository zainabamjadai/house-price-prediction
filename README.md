# house-price-prediction

\# California House Price Prediction



\## Overview



This project predicts California house prices using machine learning regression models. The workflow includes data cleaning, exploratory data analysis (EDA), feature engineering, outlier handling, feature scaling, model training, and model evaluation.



The objective of this project is to understand the factors affecting house prices and compare multiple regression algorithms to identify the best-performing model.



\---



\## Dataset



California Housing Dataset



\### Features



\- Longitude

\- Latitude

\- Housing Median Age

\- Total Rooms

\- Total Bedrooms

\- Population

\- Households

\- Median Income

\- Ocean Proximity



\### Target Variable



\- Median House Value



\---



\## Project Workflow



\### Data Exploration



\- Dataset inspection

\- Missing value analysis

\- Correlation analysis

\- Data visualization



\### Data Preprocessing



\- Missing value handling

\- One-hot encoding

\- Feature scaling



\### Feature Engineering



Created:



\- Rooms per Household

\- Bedrooms per Room

\- Population per Household



\### Outlier Handling



Used the IQR method to cap extreme values while preserving records.



\---



\## Models Trained



\- Linear Regression

\- Ridge Regression

\- Lasso Regression

\- Random Forest Regressor



\---



\## Evaluation Metrics



\- Mean Absolute Error (MAE)

\- Root Mean Squared Error (RMSE)

\- R² Score



\---



\## Results



| Model | R² Score |

|---------|---------|

| Linear Regression | 0.60 |

| Ridge Regression | 0.60 |

| Lasso Regression | 0.60 |

| Random Forest | 0.81 |



\### Best Model



Random Forest Regressor achieved the highest performance with an R² score of 0.81.



\---



\## Technologies Used



\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- Seaborn

\- Scikit-learn



\---



\## Project Structure



house-price-prediction/



├── README.md



├── california\_house\_pred.ipynb



├── requirements.txt



└── images/



\---



\## Future Improvements



\- Hyperparameter tuning

\- Cross-validation

\- Model deployment using Streamlit or Flask

\- Experimenting with XGBoost and LightGBM

