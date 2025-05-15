# 🚗 Car Price Estimation ML Model

Welcome to the **Car Price Estimation ML Model** project! This application leverages machine learning techniques to predict the selling price of used cars based on various features. It's designed to assist users in making informed decisions when buying or selling vehicles.

🔗 **Live Demo**: [Streamlit App](https://ksy2912-car-price-est-ml-model-app-pais2a.streamlit.app/)

---
## 🖼️ App UI Preview

Below is a screenshot of the Streamlit interface:

![App UI](app_ui_screenshot.png)![image](https://github.com/user-attachments/assets/3deab9dc-9f5e-4444-9ae1-a0a178c99f78)


---
## 📂 Project Structure

The repository comprises the following key files:

- `Car_Price_Model.ipynb`: Jupyter Notebook containing data preprocessing, exploratory data analysis (EDA), model training, and evaluation.
- `Cardetails.csv`: Dataset used for training and testing the model.
- `app.py`: Streamlit application script for user interaction and prediction.
- `model.pkl`: Serialized machine learning model saved using pickle.
- `requirements.txt`: List of Python dependencies required to run the application.

---

## 📊 Dataset Overview

The dataset `Cardetails.csv` includes information about used cars, with features such as:

- **Car_Name**: Name of the car.
- **Year**: Year of manufacture.
- **Selling_Price**: Price at which the car is being sold.
- **Present_Price**: Current ex-showroom price of the car.
- **Kms_Driven**: Distance completed by the car in kilometers.
- **Fuel_Type**: Type of fuel used (Petrol, Diesel, CNG).
- **Seller_Type**: Type of seller (Dealer, Individual).
- **Transmission**: Transmission type (Manual, Automatic).
- **Owner**: Number of previous owners.

---

## 🧠 Machine Learning Model

The machine learning pipeline involves:

1. **Data Preprocessing**:
   - Handling missing values.
   - Encoding categorical variables using techniques like One-Hot Encoding.
   - Feature scaling for numerical variables.

2. **Model Selection**:
   - Evaluated multiple regression models.
   - Selected the model with the best performance metrics.

3. **Model Training**:
   - Trained the selected model on the processed dataset.
   - Evaluated using metrics like R² score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

4. **Model Serialization**:
   - Saved the trained model as `model.pkl` for deployment.

---

## 🌐 Streamlit Application

The `app.py` script creates an interactive web application using Streamlit, allowing users to input car details and receive price predictions.

### Features:

- User-friendly interface for inputting car attributes.
- Real-time price prediction based on user inputs.
- Display of predicted price with intuitive visuals.

### How to Run Locally:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/ksy2912/Car_Price_Est_Ml_Model.git
   cd Car_Price_Est_Ml_Model
   ```

2. **Create a Virtual Environment** (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**:

   ```bash
   streamlit run app.py
   ```

5. **Access the App**:

   Open your browser and navigate to `http://localhost:8501`.

---

## 📈 Model Performance

The selected model achieved the following performance metrics on the test set:

- **R² Score**: *e.g., 0.92*
- **MAE**: *e.g., ₹1.2 lakhs*
- **RMSE**: *e.g., ₹1.5 lakhs*

*Note: Replace the above metrics with actual values from your model evaluation.*

---

## 📌 Future Enhancements

- Incorporate more features like car condition, location, and service history.
- Implement advanced algorithms like XGBoost or LightGBM for improved accuracy.
- Deploy the application using platforms like Heroku or AWS for broader accessibility.

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/YourFeature`.
3. Commit your changes: `git commit -m 'Add your feature'`.
4. Push to the branch: `git push origin feature/YourFeature`.
5. Open a pull request.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 📬 Contact

For any inquiries or feedback, please contact [your email address].

---
