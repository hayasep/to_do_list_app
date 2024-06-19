
# To-Do List Application

A simple to-do list application built with Flask and SQLite.

## Features

- Add, edit, delete, and mark tasks as complete.
- Tasks are stored in an SQLite database.
- Responsive design for mobile and desktop.

## Technologies Used

- Python
- Flask
- SQLite
- HTML, CSS

## Running the Application Locally

1. **Clone the repository**:

   git clone https://github.com/your-username/to_do_list_app.git
   cd to_do_list_app


2. **Install dependencies**:

   pip install -r requirements.txt


3. **Initialize the database**:

   python
   
   from app import db
   
   db.create_all()
   
   exit()


5. **Run the application**:

   python app.py


6. **Open the application in your browser**:
   - Navigate to `http://127.0.0.1:5000/`.



## License

This project is licensed under the MIT License.
