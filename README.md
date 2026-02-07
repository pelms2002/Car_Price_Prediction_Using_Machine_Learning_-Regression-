🚗 Car Price Prediction Using Machine Learning (Regression)
📌 Project Overview

This project applies machine learning regression techniques to predict car prices (Amount in Million ₦) based on vehicle attributes. Since the target variable is numerical, the problem is treated as a regression task.

The project is implemented in Python using Google Colab and follows a complete end-to-end machine learning workflow suitable for beginners.

📊 Dataset Description

The dataset contains the following features:

Location – Where the car is sold

Maker – Car brand

Year – Year of manufacture

Colour – Car color

Type – Car type (e.g., Brand New, Foreign Used)

Distance_Km – Distance driven in kilometers

Amount (Million ₦) – Target variable

⚙️ Project Workflow
1️⃣ Data Loading

Dataset loaded from Google Drive using Pandas.

2️⃣ Data Cleaning

Removed irrelevant column (Model)

Removed duplicate records

Fixed structural errors (text formatting)

Handled missing values using median imputation

3️⃣ Exploratory Data Analysis (EDA)

Car price distribution

Price comparison by car type and location

Relationship between car year and price

4️⃣ Feature Encoding

Categorical features encoded using Label Encoding

5️⃣ Feature Scaling

Numerical features scaled using StandardScaler

6️⃣ Model Training

The following regression models were trained:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

7️⃣ Model Evaluation

Models were evaluated using:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

8️⃣ Prediction

The trained model predicts the price of a new car based on given features.

🏆 Results

Gradient Boosting Regressor achieved the best overall performance based on evaluation metrics.

The model can effectively estimate car prices given vehicle characteristics.

🧰 Tools & Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Google Colab

📂 Project File

Car_Price_Prediction_Using_Machine_Learning_(Regression).ipynb

✅ Conclusion

This project demonstrates how regression models can be used to predict car prices using real-world data. It is designed to be beginner-friendly and suitable for students learning machine learning fundamentals.
