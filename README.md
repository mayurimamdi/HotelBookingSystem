# HotelBookingSystem

📌 Project Overview
This project explores the Hotel Booking Demand dataset to understand booking patterns and identify factors influencing hotel booking cancellations. The analysis includes data cleaning, exploratory data analysis (EDA), feature engineering, and lays the foundation for predictive modeling.
The goal is to extract actionable insights that could help hotels reduce cancellations and optimize booking strategies.
🗂 Dataset
Source: Hotel Booking Demand Dataset
Size: ~119,000 bookings
Hotels:
Resort Hotel
City Hotel
Time Period: 2015–2017
Key Features:
Booking details (lead time, arrival date, stay duration)
Customer information (adults, children, country)
Booking channel (agent, company, deposit type)
Target variable: is_canceled
🧹 Data Cleaning & Preprocessing
The following preprocessing steps were applied:
Handled missing values:
country: Missing values filled with "Unknown"
agent: Missing values indicate direct bookings
company: Missing values indicate non-corporate bookings
Preserved raw data and applied cleaning through reproducible code
Ensured data consistency for downstream analysis and modeling
📌 Missing values were treated as meaningful categories rather than dropped, as missingness itself may carry predictive value.
🔍 Exploratory Data Analysis (EDA)
EDA was performed to uncover patterns such as:
Cancellation trends by hotel type
Impact of lead time on cancellations
Country-wise booking behavior
Relationship between booking channels and cancellations
Seasonal trends in arrivals and cancellations
Visualizations were created using Matplotlib and Pandas.
🛠 Tools & Technologies
Python
Pandas
NumPy
Matplotlib
Jupyter Notebook
Scikit-learn (for preprocessing and modeling)
📈 Future Work
Feature encoding and scaling
Build machine learning models for cancellation prediction
Model evaluation using appropriate metrics (accuracy, precision, recall, ROC-AUC)
Hyperparameter tuning
Feature importance analysis
