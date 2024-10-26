# Task Management Application

## Overview
The Task Management Application is a web-based tool designed to help users manage their tasks effectively. Users can create, update, delete, and filter tasks based on priority and due date. The application features a clean and responsive UI built using React, Tailwind CSS, and Next.js for the frontend, with a Node.js and Express backend.

## Features
- Create, update, and delete tasks
- Filter tasks by title and priority
- Toggle task status between "pending" and "completed"
- Responsive design with a minimal light and dark theme

## Technologies Used
- **Frontend**: 
  - React
  - CSS
- **Backend**: 
  - Node.js
  - Express
  - MongoDB (with Mongoose for object modeling)

## Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- MongoDB database

### Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/task-manager-app.git
Navigate to the frontend directory:

bash
Copy code
cd task-manager-app/frontend
Install frontend dependencies:

bash
Copy code
npm install
Run the frontend application:

bash
Copy code
npm run dev
Navigate to the backend directory:

bash
Copy code
cd ../backend
Install backend dependencies:

bash
Copy code
npm install
Create a .env file in the backend directory and set your environment variables:

makefile
Copy code
MONGODB_URI=<your_mongodb_connection_string>
Run the backend application:

bash
Copy code
node server.js
API Endpoints
GET /api/tasks - Retrieve all tasks
POST /api/tasks - Create a new task
PUT /api/tasks/:id - Update a task
DELETE /api/tasks/:id - Delete a task
Usage
Access the frontend through your browser at http://localhost:3000.
Use the form to add new tasks.
Filter tasks using the search bar and priority dropdown.
Manage tasks by updating their status or deleting them.
Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs or feature requests.

