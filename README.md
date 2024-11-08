
# Early Prediction of Chronic Kidney Disease

## Project Overview
This project aims to predict the likelihood of Chronic Kidney Disease (CKD) using machine learning. The web application allows users to input their health data and provides real-time predictions. The goal is to facilitate early diagnosis and treatment.

## Features
- **Web Interface**: Built with HTML, CSS, and JavaScript to provide a user-friendly experience.
- **Machine Learning Model**: Python (Scikit-learn) is used to create a model that predicts CKD based on various health parameters.
- **Real-Time Predictions**: Users can input data and receive immediate predictions about CKD.
- **Data Visualization**: The app includes visual representations of the user's health data and predictions.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask)
- **Machine Learning**: Scikit-learn, Pandas, NumPy
- **Data Visualization**: Matplotlib, Seaborn
- **Deployment**: Flask
- **Version Control**: Git

## Project Structure
- **static/**: This directory contains all static files, including CSS for styling and JavaScript for client-side functionality.
- **templates/**: Contains the HTML templates used for rendering the web application interface.
- **model/**: Holds the trained machine learning model in a serialized format (pickle).
- **app.py**: The main application file that contains the server code to handle requests and predictions.
- **README.md**: A documentation file that provides an overview of the project, installation instructions, and usage details.
- **requirements.txt**: Lists all necessary Python packages that the application depends on, making it easy to set up the environment.

## How It Works
- **Input**: The user enters relevant medical data, such as age, blood pressure, serum creatinine levels, and other health-related information.
- **Prediction**: The machine learning model processes the input data and predicts the likelihood of CKD.
- **Output**: The user is presented with a result indicating whether they are at risk for CKD, along with a confidence score that reflects the model's certainty in its prediction.

## Machine Learning Model
The machine learning model was trained using a publicly available dataset on Chronic Kidney Disease. The data preprocessing steps included:

- **Handling missing values** to ensure the integrity of the dataset.
- **Scaling features** to normalize the input data for better model performance.
- **Encoding categorical data** to convert non-numeric information into a format suitable for the model.

Several algorithms were tested during model training, with Random Forest being the final choice due to its high accuracy and efficiency. The model evaluation metrics include:

- **Accuracy**: Approximately 90%
- **Precision**: Approximately 85%
- **Recall**: Approximately 88%
## How to Run the Project
To run this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/gayathrinadendla/Early-Prediction-of-Chronic-Kidney-Disease.git
   cd Early-Prediction-of-Chronic-Kidney-Disease

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt

3. Run this application
    ```bash
    python app.py

 Access the application: Open your web browser and navigate to http://127.0.0.1:5000/.

 ## Dataset
- **Source**: The dataset was provided by Smart Internz.
- **Description**: The dataset contains various medical attributes such as blood pressure, age, serum creatinine levels, and other relevant health indicators.


## Challenges Faced
- **Handling Missing Data**: Ensured the integrity of the dataset by appropriately addressing missing values.
- **Hyperparameter Tuning**: Optimized model performance through careful tuning of hyperparameters.
- **User Interface Design**: Developed a responsive and interactive web interface suitable for non-technical users.


  ## Conclusion

The **Early Prediction of Chronic Kidney Disease** project exemplifies the power of machine learning in healthcare. By providing a user-friendly web application that enables real-time predictions of CKD risk, we aim to facilitate early diagnosis and timely intervention. This proactive approach has the potential to significantly improve patient outcomes by enabling healthcare providers and patients to make informed decisions based on predictive analytics.

Through rigorous model training and evaluation, we have demonstrated a commitment to accuracy and reliability in our predictions. Future enhancements, including the integration of advanced machine learning algorithms and mobile accessibility, will further enhance the application's effectiveness and reach.

As we continue to refine and expand this project, we are dedicated to contributing to the field of health informatics and supporting efforts to combat chronic diseases like CKD.


