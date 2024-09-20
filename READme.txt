 Project Name: Data Analysis and Visualization with Flask, MongoDB, and Jupyter 

 Project Description:
    This project involves creating a survey form for collecting participants data to analyze their income spending in preparation for a new product launch in the healthcare industry. The project encompasses web development with Flask, data storage with MongoDB, data processing with Python, and data visualization using Jupyter notebooks.

 Requirements:
     Python
     Flask Library
     Jupyter notebook
     Powerpoint

 Project Overview:

1. Web Development with Flask:
    - Develop a simple webpage called "Flask_app.py" using Flask to collect user data.

2. Data Storage with MongoDB:
    - Store user details, including Name, Age, Gender, Total Income, and Expenses, in MongoDB.

3. Data Processing with Python:
    - Create a Python class named "User". This can be found in `process_data.py` script.
    - Loop through the collected data and store it in a CSV file.

4. Data Visualization:
    - Open data_visualization.ipynb script
    - Perform visualizations in a Jupyter notebook, including:
    - Loading required libraries like pandas, matplotlib, and seaborn.
    - Showing the ages with the highest income.
    - Showing the gender distribution across spending categories.
    - Export the charts for use in a PowerPoint presentation for client use.
    - An instance is in a powerpoint file named `powerpoint_presentation.pptx`


 Project Structure:
    - Flask_app.py: Flask application for collecting user data.
    - template/index.html: HTML template for the survey webpage.
    - process_data.py: Python class for representing user data.
    - user_data.csv: CSV file to store user data.
    - data_visualization.ipynb: Jupyter notebook for data visualization.
    - charts: Folder containing exported charts for PowerPoint presentation.
    - README.md: Project overview, structure, and Instructions.


** Instructions for Running the Project:
    - Ensure Python is installed on your system.
    - Install Flask and other required dependencies.
    - Start the MongoDB server.
    - Run the Flask application using python Flask_app.py.
    - Access the survey webpage in your browser using the localhost -> http://127.0.0.1:5000
    - Submit the Income Spending Data to store user data in MongoDB.
    - Run the data processing script `process_data.py` to store data in a CSV file.
    - Open the Jupyter notebook for data visualization and execute the cells.
    - Export the charts for use in a PowerPoint presentation.
    - Open `powerpoint_presentation.pptx` to view a powerpoint presentation.

