# Student Exam Performance Predictor 🎓📊  
## This project predicts student's math scores based on various features such as *gender, ethnicity, parental education, lunch type, test preparation course, reading score, and writing score*. The model is built using Machine Learning and deployed using ***Flask***.

📌 Features  
✅ Machine Learning model to predict math scores  
✅ Flask Web Application for user-friendly interaction  
✅ Data preprocessing and feature engineering  
✅ Uses Scikit-Learn for model training  
✅ Dockerized for easy deployment   
✅ Deployed on AWS/GCP/Heroku   

📂 Project Structure  


mlproject/  
&nbsp;&nbsp;&nbsp;&nbsp;│-- **src/**  
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;├── **components/**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Core components for data processing  
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;├── **pipeline/**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Model training & prediction pipelines  
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;├── **utils.py**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Helper functions  

&nbsp;&nbsp;&nbsp;&nbsp;│-- **templates/**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# HTML files (Flask UI)  
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;├── **index.html**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Home page  
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;├── **home.html**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Input form page  
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;├── **result.html**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Prediction result page  

&nbsp;&nbsp;&nbsp;&nbsp;│-- **static/**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# CSS, JavaScript, images  

&nbsp;&nbsp;&nbsp;&nbsp;│-- **app.py**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Main Flask app  
&nbsp;&nbsp;&nbsp;&nbsp;│-- **model.pkl**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Trained Machine Learning model  
&nbsp;&nbsp;&nbsp;&nbsp;│-- **requirements.txt**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Dependencies  
&nbsp;&nbsp;&nbsp;&nbsp;│-- **README.md**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Project documentation  
&nbsp;&nbsp;&nbsp;&nbsp;│-- **.gitignore**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Git ignore file  


### ⚙️ Setup and Installation

1️⃣ Clone the Repository  
git clone https://github.com/shrstwr/mlproject.git
cd mlproject

2️⃣ Create a Virtual Environment (Recommended)  
'python -m venv venv'  
source 'venv/bin/activate'  &nbsp;&nbsp;&nbsp;&nbsp;   # For Mac/Linux  
'venv\Scripts\activate'    &nbsp;&nbsp;&nbsp;&nbsp;  # For Windows

3️⃣ Install Dependencies  
'pip install -r requirements.txt'

4️⃣ Run the Application  
'python application.py'  
Now, open your browser and go to:  
🔗 http://127.0.0.1:5000/

### 🛠 Model Training
Data is processed and transformed using StandardScaler and OneHotEncoder  
Model is trained using Linear Regression  
Pickle (.pkl) file stores the trained model for fast inference  

### 🚀 Deployment  
Deploy using Heroku, AWS, or any cloud provider  
Dockerize for easy deployment  

### 🤝 Contributing  
Feel free to fork this repository and contribute by:    
- Improving the model  
- Enhancing UI/UX  
- Adding new features  

### 📞 Contact  
🔹 GitHub: shrstwr &nbsp;&nbsp;&nbsp;&nbsp;
🔹 Email: srastwr@gmail.com &nbsp;&nbsp;&nbsp;&nbsp;
🔹 LinkedIn: Shreyas Tiwari &nbsp;&nbsp;&nbsp;&nbsp;
