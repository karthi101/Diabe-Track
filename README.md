🩺 Diabe Track – Diabetes Prediction System
📖 Overview

Diabe Track is a web-based application built with Django and Machine Learning that predicts the likelihood of diabetes based on user-input health parameters.
It provides a simple interface for users to register, log in, and check their diabetes risk using a trained ML model.

✨ Features

🔐 User Authentication – Register, Login, and Logout

📊 Health Data Input – Users can enter medical details like glucose level, BMI, age, etc.

🤖 ML Model Integration – Predicts diabetes using trained machine learning algorithms

📱 Responsive Web UI – Clean and user-friendly interface

💾 Database Support – Stores user details securely

🛠️ Tech Stack

Backend: Django (Python)

Frontend: HTML, CSS, Bootstrap

Database: SQLite (default Django DB)

Machine Learning: Scikit-learn, Pandas, NumPy

🚀 Installation & Setup

Clone the Repository

git clone https://github.com/your-username/diabe-track.git
cd diabe-track


Create a Virtual Environment

python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows


Install Dependencies

pip install -r requirements.txt


Apply Migrations

python manage.py migrate


Run the Server

python manage.py runserver


Access the App
Open your browser and go to:

http://127.0.0.1:8000/



Adding data visualization dashboards

Advanced ML models for higher accuracy
