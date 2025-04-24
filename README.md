Telecom Data Analysis Project
Overview
This project involves analyzing a telecommunication dataset to provide insights into user behavior, engagement, experience, and satisfaction. The goal is to help a wealthy investor make an informed decision about purchasing TellCo, a mobile service provider in the Republic of Pefkakia.

Project Structure
data/: Contains the dataset used for analysis.
scripts/: Contains Python scripts for data preprocessing, analysis, and model training.
models/: Contains the trained models and any related files.
notebooks/: Contains Jupyter notebooks used for exploratory data analysis and visualization.
reports/: Contains the final report and presentation slides.
Dockerfile: Dockerfile to build the project as a Docker image.
requirements.txt: List of dependencies required to run the project.
app.py: Flask application for serving the model and making predictions.
Setup Instructions
Prerequisites
Python 3.8 or higher
Docker (optional, for containerization)
MLflow (for model tracking)
Flask (for serving the model)
Installation
Clone the repository:


Create a virtual environment and activate it:


Install the required dependencies:


Running the Project
Data Preprocessing and Analysis:

Run the data preprocessing script:

Run the analysis scripts:

Model Training and Tracking:

Train the model and track it with MLflow:

Serving the Model:

Start the Flask application:

Using Docker (optional):

Build the Docker image:

Run the Docker container:

Accessing the MLflow UI
To monitor the model's performance and track experiments, start the MLflow server:


Access the MLflow UI at http://localhost:5000.

Project Components
Data Analysis
User Overview Analysis: Identifies the top handsets and manufacturers, and provides insights into user behavior.
User Engagement Analysis: Analyzes user engagement metrics and clusters users based on their engagement levels.
Experience Analytics: Evaluates user experience based on network parameters and device characteristics.
Satisfaction Analysis: Combines engagement and experience metrics to assess user satisfaction and predict future satisfaction scores.
Model Deployment
The model is deployed using Flask and can be accessed via a REST API for making predictions.
Docker is used for containerization to ensure consistency across different environments.
Results and Recommendations
Summarize the key findings from the analysis.
Provide recommendations on whether the investor should purchase TellCo based on the data insights.
Highlight any limitations of the analysis and suggest areas for further research.
