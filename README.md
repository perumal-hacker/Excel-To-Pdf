
## Excel Table Generator
Welcome to the Excel Table Generator! This is a simple Flask application that allows users to upload Excel files, view the data, filter it by grade, and download the results as PDF files.

# Features
Upload Excel files
Display data in a web interface
Filter data based on a specified grade
Download the entire data or filtered data as a PDF

# Technologies Used
Flask: A lightweight WSGI web application framework in Python.
Pandas: A powerful data manipulation and analysis library for Python.
FPDF: A Python class for generating PDF files.

# Installation
Follow these steps to install and run the application:

Clone the repository:

 
git clone https://github.com/yourusername/excel-table-generator.git
cd excel-table-generator
Create a virtual environment (optional but recommended):

 
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required packages:

 
pip install flask pandas fpdf
Run the application:

 
python app.py
Open your web browser and go to http://127.0.0.1:5000/

# Usage
Upload an Excel file using the provided input form.
Once the file is uploaded, the data will be displayed in a table format.
Use the filter section to filter the data based on grades.
Download the entire dataset or the filtered dataset in PDF format using the provided buttons.

# Example Excel File Structure
Your Excel file should have a column named Grade for filtering. Here’s an example structure:

| Name | Grade | Score |
| John Doe | A | 90 | 
| Jane Smith| B | 85 | 
| Mark Brown| C | 70 |

Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please fork the repository and create a pull request 
