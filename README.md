# 🚗 Vehicle MPG Prediction

A Machine Learning application that predicts a vehicle's **Miles Per Gallon (MPG)** using a trained regression model and an interactive Streamlit web interface.

The project demonstrates the complete process of integrating a trained Machine Learning model into a user-friendly application.

---

## 📌 Project Overview

Fuel efficiency is an important characteristic of a vehicle.

The purpose of this project is to build a Machine Learning application that can estimate a vehicle's **MPG (Miles Per Gallon)** based on vehicle-related input features.

The trained Machine Learning model is stored in:

```text
model.pkl
```

and is integrated with the Streamlit application through:

```text
app.py
```

---

## 🎯 Problem Statement

The objective is to develop a Machine Learning model capable of predicting a vehicle's fuel efficiency based on the available vehicle characteristics.

The project focuses on transforming a trained Machine Learning model into an interactive application where users can provide vehicle information and receive an MPG prediction.

---

## 💡 Objective

The main objectives of this project are:

* Build a vehicle MPG prediction model.
* Use vehicle-related features to estimate fuel efficiency.
* Save the trained model for later use.
* Develop an interactive Streamlit application.
* Allow users to enter vehicle information.
* Display the predicted MPG in an easy-to-understand format.

---

## 🔄 Project Workflow

```text
Vehicle Dataset
       ↓
Data Preprocessing
       ↓
Feature Selection
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Save Trained Model
       ↓
model.pkl
       ↓
Streamlit Application
       ↓
User Input
       ↓
MPG Prediction
```

---

## 🤖 Machine Learning Model

The trained model is stored in:

```text
model.pkl
```

The Streamlit application loads this model and uses it to generate predictions from user-provided vehicle information.

> The exact regression algorithm and training methodology should be documented here based on the original model-training notebook/script. Avoid claiming a specific algorithm unless it is confirmed from the training code.

---

## 🖥️ Streamlit Application

The application is implemented in:

```text
app.py
```

The Streamlit interface provides a simple way for users to enter vehicle information and obtain an estimated MPG value.

### Application Flow

```text
Enter Vehicle Information
          ↓
Submit Input
          ↓
Load Trained Model
          ↓
Generate Prediction
          ↓
Display Estimated MPG
```

---

## 📸 Application Screenshots

### Application Interface

![Vehicle MPG Prediction Application](screenshots/app-home.png)

### Prediction Result

![Vehicle MPG Prediction Result](screenshots/prediction-result.png)

> Add screenshots from the actual running Streamlit application to the `screenshots` directory.

---

## 📁 Project Structure

```text
Vehicle_MPG_Prediction/
│
├── app.py
│   └── Streamlit application
│
├── model.pkl
│   └── Trained Machine Learning model
│
├── requirements.txt
│   └── Python dependencies
│
├── .gitignore
│   └── Files excluded from Git
│
├── README.md
│   └── Project documentation
│
└── screenshots/
    ├── app-home.png
    └── prediction-result.png
```

---

## 🛠️ Technologies Used

| Technology   | Purpose              |
| ------------ | -------------------- |
| Python       | Programming language |
| Pandas       | Data processing      |
| NumPy        | Numerical operations |
| Scikit-learn | Machine Learning     |
| Streamlit    | Web application      |
| Pickle       | Model serialization  |
| Git & GitHub | Version control      |

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/imrannadaf250/Vehicle_MPG_Prediction.git
```

### 2. Navigate to the project directory

```bash
cd Vehicle_MPG_Prediction
```

### 3. Create a virtual environment

#### Windows

```bash
python -m venv .venv
```

Activate it:

```bash
.venv\Scripts\activate
```

#### Linux / macOS

```bash
python3 -m venv .venv
```

Activate it:

```bash
source .venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Start the Streamlit application:

```bash
streamlit run app.py
```

After running the command, Streamlit will provide a local URL that can be opened in your browser.

---

## 📝 How to Use

1. Start the Streamlit application.
2. Enter the required vehicle information.
3. Submit the input.
4. The application loads the trained Machine Learning model.
5. The model generates an MPG prediction.
6. The predicted MPG is displayed in the application.

---

## 📊 Results

The application generates an estimated **Miles Per Gallon (MPG)** value for the supplied vehicle information.

The exact model performance metrics should be added here after verifying the original model-training process.

Recommended metrics for a regression model include:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

> Numerical results should only be added after confirming them from the actual model-training process.

---

## 🔮 Future Improvements

Possible improvements include:

* Add model evaluation metrics to the application.
* Add input validation.
* Improve the user interface.
* Add visualizations for vehicle characteristics.
* Display prediction confidence or error information where appropriate.
* Add multiple regression models for comparison.
* Add downloadable prediction results.
* Add automated model retraining.
* Add a dedicated dataset and training notebook to make the project fully reproducible.

---

## ⚠️ Important Note

This project is intended for **educational and portfolio purposes**.

The predicted MPG value is an estimate generated by a Machine Learning model and should not be treated as an exact real-world fuel-economy measurement.

---

## 👨‍💻 Author

**Imran Nadaf**

B.Tech in Computer Science and Engineering
Dr. Daulatrao Aher College of Engineering, Karad — 2026

### Connect With Me

* GitHub: https://github.com/imrannadaf250
* LinkedIn: https://www.linkedin.com/in/imran-nadaf-6aa743311/

---

## ⭐ Project Purpose

This project demonstrates practical experience in:

* Python
* Machine Learning
* Regression
* Model serialization
* Streamlit application development
* Git and GitHub

It represents part of my learning journey toward **Data Science, Machine Learning, and practical software development**.
