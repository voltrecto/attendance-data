# Attendance Data Processing with Pandas

### Overview
This repository contains a Jupyter notebook showcasing a Python script for processing attendance data using the Pandas library. The script is designed to streamline the attendance reporting process, converting raw schedule and phone data into a format suitable for upload to an SQL database for use in an attendance dashboard.

### Background
The provided code is a modified version developed to improve an existing attendance processing workflow. The techniques and data formats applied are similar to those used in a real-world scenario. However, the actual data, including names, numbers, and values, has been randomly generated for illustration and confidentiality purposes.

### Features
1. Schedule Extraction: Extracts and consolidates schedule data from multiple Excel files, handling duplicates and filtering relevant information.
2. Login/Logout Data Processing: Processes phone data to extract login/logout times within a specified period around scheduled shifts, creating a formatted dataset.

### Usage
1. This notebook was created in Google Colaboratory, an online platform for Jupyter notebooks. Make sure to run the cells sequentially in a Colab environment.
2. Customize the file paths, date, and other parameters in the notebook as needed.
3. Run the notebook cell by cell to execute the attendance data processing.
4. The resulting datasets (schedule_data.csv and lilo_data.csv) can be used for further analysis or uploaded to an SQL database.

### Note
The notebook includes explanatory comments for clarity. Feel free to explore, modify, and adapt the code to suit your specific requirements.
