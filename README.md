# Exploring Additional Features Flask

This is a simple Flask application for managing transactions.

## Description

The app allows you to perform basic CRUD (Create, Read, Update, Delete) operations on transactions. It provides web pages to view, add, edit, and delete transactions.

## Installation

To run this Flask app, follow these steps:

1. Clone the repository:
2. Navigate into the project directory:
3. Install the required dependencies (assuming you have Python installed):
   
## Usage

1. Run the Flask app:
2. Open a web browser and go to http://localhost:5000/ to view the list of transactions.
3. From the main page, you can:
   
## Routes

- GET `/` - Displays the list of transactions.
- GET `/add` - Renders a form to add a new transaction.
- POST `/add` - Adds a new transaction to the list.
- GET `/edit/<int:transaction_id>` - Renders a form to edit a transaction.
- POST `/edit/<int:transaction_id>` - Updates an existing transaction.
- GET `/delete/<int:transaction_id>` - Deletes a transaction.
  
## Sample Data

The app comes with some sample transaction data for demonstration purposes:
```python
transactions = [
    {'id': 1, 'date': '2023-06-01', 'amount': 100},
    {'id': 2, 'date': '2023-06-02', 'amount': -200},
    {'id': 3, 'date': '2023-06-03', 'amount': 300}
]
```
Feel free to modify, add, or remove transactions as needed.

## Technologies Used
- Python
- Flask
