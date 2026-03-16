EduLib
EduLib is a digital library management system developed as the final project for CSC3323 – Software Engineering at Al Akhawayn University.
The platform allows students to easily access and manage academic resources through a web interface.
Features
User authentication (Student and Admin roles)
Book catalog and genre management
Book borrowing and checkout history tracking
Integrated chatbot using GPT4All and LLaMA 3
Technologies Used
Python
Flask
SQLite
HTML, CSS, JavaScript
Running the Project
Install GPT4All from:
https://www.nomic.ai/gpt4all
Download and install the LLaMA 3 model inside GPT4All.

Run the application:
python app.py 

Project Structure
instance/
    contains the SQLite database file

static/
    css/        -> page styling (styles.css)
    js/         -> JavaScript for chatbot and interactivity
    photos/     -> images used in the interface

templates/
    admin/      -> HTML pages for admin users
    non_admin/  -> HTML pages for student users
    signup.html
    index.html  -> login page

app.py
    backend application logic


Database Models
The system uses SQLite with the following models:
User
Book
Genre
Role
BookGenre
UserRole
BookCheckoutHistory


Notes
This project was developed as part of a Software Engineering course at Al Akhawayn University in collaboration with a team of students.

    




