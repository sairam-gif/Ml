🌱 Crop Recommendation System

The Crop Recommendation System is a machine learning project designed to assist farmers in selecting the most suitable crop for cultivation based on environmental and agricultural factors. By analyzing parameters such as State, District, Season, Crop Year, Area, and Production data, the system leverages historical agricultural datasets and predictive modeling to provide accurate crop recommendations.

🔑 Key Features

Uses Random Forest Classifier with hyperparameter tuning for improved accuracy

Incorporates Label Encoding for handling categorical features (State, District, Season, Crop)

Provides dynamic input selection (State → District → Season)

Visualizes crop data distribution with interactive pie charts

Built with Flask for web-based user interaction

⚙️ Tech Stack

Python (Pandas, NumPy, Scikit-learn, Joblib)

Flask (for web app deployment)

Matplotlib / Plotly (for crop visualization)

Machine Learning Model: Random Forest (saved as crop_recommendation_improved.pkl)

📊 Workflow

Data Preprocessing: Load dataset (crop_data.csv) → Clean & encode categorical data

Model Training: Train Random Forest model → Save model & encoders (state_encoder.pkl, district_encoder.pkl, season_encoder.pkl, crop_encoder.pkl)

Prediction: User inputs State, District, and Season → System predicts the best crop

Visualization: Pie chart shows the distribution of recommended crops in the selected region

🌍 Applications

Helps farmers maximize yield by recommending the right crop for their region & season

Can be extended with weather data, soil health data, and real-time IoT inputs

Useful for agricultural planning & decision-making at both local and government levels
