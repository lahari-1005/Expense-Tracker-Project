EXPENSE TRACKER



The Expense Tracker is a user-friendly application designed to help individuals and businesses monitor their spending habits. By providing an intuitive interface to record, track, and analyze expenses, the application enables users to make informed financial decisions and improve their budgeting skills.
Features
Expense Recording: Add daily expenses with details such as category, amount, and date.
Expense Categories: Organize expenses under customizable categories like Food, Travel, Bills, etc.
Analytics Dashboard: View detailed reports and visualizations of spending patterns.
Search and Filter: Easily search and filter expenses by category, date, or amount.
Budget Alerts: Set spending limits and receive alerts when approaching the threshold.
Data Export: Export expense data in formats such as CSV for external use.
Installation
Follow the steps below to set up and run the application locally.

Prerequisites
Ensure you have the following installed:

Node.js
MongoDB
Steps
Clone the repository:

bash
Copy
Edit
git clone https://github.com/lahari-1005/expense-tracker.git  
cd expense-tracker  
Install dependencies:

Backend:
bash
Copy
Edit
cd server  
npm install  
Frontend:
bash
Copy
Edit
cd client  
npm install  
Set up environment variables:
Create a .env file in the server directory with the following content:

env
Copy
Edit
PORT=5000  
MONGO_URI=your_mongodb_connection_string  
JWT_SECRET=your_secret_key  
Run the application:

Start MongoDB (if not running already).
Start the backend server:
bash
Copy
Edit
cd server  
npm start  
Start the frontend server:
bash
Copy
Edit
cd client  
npm start  
API Endpoints
User Authentication
POST /api/users/register: Register a new user.
POST /api/users/login: Log in a user and get a JWT.
Expenses
GET /api/expenses: Get all expenses for a user.
POST /api/expenses: Add a new expense.
PUT /api/expenses/:id: Update an expense by ID.
DELETE /api/expenses/:id: Delete an expense by ID.
Usage
Navigate to the application in your browser (default: http://localhost:3000).
Sign up for a new account or log in to your existing one.
Start adding your expenses and explore the analytics features.
Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch:
bash
Copy
Edit
git checkout -b feature/your-feature-name  
Commit your changes:
bash
Copy
Edit
git commit -m "Add your description here"  
Push your branch:
bash
Copy
Edit
git push origin feature/your-feature-name  
Open a pull request.




