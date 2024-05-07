# Flight Price Prediction using Amazon SageMaker

## Overview:

- The project aims to develop and deploy machine learning models for predicting flight ticket prices using Amazon SageMaker. This involves building a robust model that can accurately forecast the cost of a flight based on the various input features. The project also leverages the power of Amazon SageMaker for efficient training, optimization of the machine learning models.

## Methodologies:

**1. Data Collection and Preprocessing**: Acquired and preprocessed extensive datasets containing historical flight information, such as prices, routes, departure and arrival times, and airlines.

**2. Exploratory Data Analysis (EDA)**: Conducted thorough EDA using pandas and numpy to uncover patterns, trends, and potential features for model development.

**3. Model Development and Fine-Tuning**: Created and optimized machine learning models, with a focus on the high-performance XGBoost algorithm for its efficiency and interpretability.

**4. Feature Engineering and Selection**: Engineered and selected impactful features from the dataset using `feature-engine` to enhance model accuracy and performance.

**5. Model Evaluation**: Assessed model performance using metrics such as mean absolute error (MAE), mean squared error (MSE), and R-squared to ensure reliability and precision.

**6. Model Deployment**: Deployed the prediction model using Streamlit, offering a user-friendly web interface where users could input flight details and receive price predictions.

## Technologies and Tools Used:

* **Libraries**: numpy, pandas, matplotlob, seaborn, scipy, feature-engine, scikit-learn
* **Machine Learning Algorithm**: Isolation Forest, Extreme Gradient Boosting (XG Boost)
* **Web Framework**: Streamlit
* **Deployment & Infrastructure**: Streamlit Cloud

## Outcomes:

**1. Accurate Price Predictions**: Developed a reliable machine learning model that predicts flight ticket prices accurately based on historical data and selected features.

**2. User-Friendly Interface**: Created a streamlined web interface using Streamlit, enabling users to input flight details and swiftly receive price predictions.

**3. Improved Model Performance**: Enhanced model accuracy through fine-tuning, feature engineering, and iterative development, leading to dependable and precise predictions.

**4. Insights into Flight Pricing**: Provided valuable insights into the factors affecting flight prices, facilitating better decision-making for travelers and airline companies.

*[Web App Link](https://flight-price-prediction-using-amazon-sagemaker.streamlit.app/)*
