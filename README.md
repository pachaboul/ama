# Aguida Multimodal Analyzer

Overview

Aguida Multimodal Analyzer is a sophisticated software tool designed to analyze and compare various types of biometric and emotional data. This application is particularly useful for researchers, psychologists, and data scientists who work with multimodal data including heart rate, eye tracking, facial emotion recognition, and conversational data. The tool provides robust data visualization, statistical analysis, and machine learning capabilities to derive insights from complex datasets.
Key Features
Data Upload and Processing:

    Upload multiple files in CSV or Excel format.
    Process and normalize data for consistency and accuracy.

Heart Rate Analysis:

    Calculate and display key statistics such as average, standard deviation, variance, skewness, and kurtosis.
    Plot heart rate data over time with normal and abnormal heart rate indicators.
    Generate detailed PDF and CSV reports.

Eye Tracking Analysis (Tobii):

    Analyze eye movement and head position data.
    Perform ANCOVA and SVM classification.
    Visualize data trends over time and generate comprehensive reports.

Facial Emotion Analysis:

    Calculate and display statistics for various Action Units (AUs).
    Plot AU values and head position over time.
    Perform SVM classification to distinguish between different facial expressions.
    Generate detailed PDF and CSV reports including statistical tables, graphs, and classification results.

Conversational Data Analysis (Dialogflow):

    Process and analyze conversational data.
    Extract key metrics such as response time, sentiment analysis, and strategy usage.
    Generate detailed reports on conversational dynamics.

Comparative Analysis:

    Compare pre-test and post-test data.
    Calculate and visualize differences in confidence, nervousness, and willingness to communicate (WtC).
    Generate reports highlighting the comparative results and statistical significance.

Technical Details
Programming Language:

    Python

Libraries and Frameworks:

    pandas for data manipulation and analysis.
    matplotlib for data visualization.
    PyQt5 for the graphical user interface.
    scipy and statsmodels for statistical analysis.
    scikit-learn for machine learning and classification.

Output Formats:

    PDF and CSV reports

Installation and Usage
Set Up the Environment:

Ensure you have Python installed (preferably in a virtual environment). Install the required libraries using the provided requirements.txt file:

sh

pip install -r requirements.txt

Run the Application:

Start the application by running the main script:

sh

python main.py

Upload Data:

Use the user interface to upload the relevant data files for heart rate, eye tracking, facial emotions, and conversational data.
Analyze and Generate Reports:

Select the analysis options and generate detailed reports in PDF and CSV formats.
Requirements
Python 3.x
Required libraries as listed in requirements.txt:

txt

# Data manipulation and analysis library
pandas==1.5.0

# Plotting and visualization library
matplotlib==3.6.0

# Python bindings for the Qt application framework
PyQt5==5.15.7

# Scientific computing and technical computing library
scipy==1.9.1

# Machine learning library
scikit-learn==1.1.3

# Statistical models library
statsmodels==0.13.2

Contact and Support

For further information, support, or to contribute to the project, please visit the project's GitHub repository.