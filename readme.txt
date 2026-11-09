Flask Hello World Application
About the Project

This is a basic web application developed using Python Flask. It displays a Hello World message on a webpage. This project demonstrates how to create a Flask application and display an HTML page using Flask's template rendering feature.

Project Structure
text
project/
│
├── main.py
├── templates/
│   └── index.html
└── static/

Files Description
main.py: The main Python file that creates the Flask application and defines the home route (/). It uses render_template() to display the HTML page.
index.html: Contains the HTML code that displays the heading "HELLO WORLD" and the message "This is a flask application".
static/: This folder is used to store static files such as CSS, JavaScript, and images. It is currently empty.
Requirements
Python 3
Flask
Installation

Install Flask using the following command:

bash
pip install flask

How to Run
Open the project folder in the terminal.
Run the following command:
bash
python main.py

Open your browser and visit:
text
http://127.0.0.1:5000/

Output

The webpage displays:

HELLO WORLD

This is a flask application.

Technologies Used
Python
Flask
HTML
Purpose

The purpose of this project is to understand the basics of Flask, including application creation, URL routing, HTML templates, and displaying web pages using Python.