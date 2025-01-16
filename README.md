# Todo Management Application: Angular + ASP.NET Core

Welcome to the Todo Management Application! Whether you're here to seize the day or procrastinate a little longer, this app is designed for you. As a React developer exploring Angular and ASP.NET Core, I created this project to manage a simple todo list right in your browser. If traditional pen and paper aren't your style, this app has you covered.

## Project Overview

This project simulates a real-world web application with advanced features, including:

- **Persistent SQL Database**: Store your todos securely.
- **Custom API with CRUD Operations**: Create, read, update, and delete todos.
- **Backend DTO Capabilities**: Includes a "secret" field for added functionality.
- **Stateful Front-End Logic**: Ensures seamless user interactions.
- **API Calls**: Facilitates smooth communication between the frontend and backend.
- **Responsive Styling**: Optimized for various devices and screen sizes.

### Future Enhancements

Plans to expand this application include:

- Adding more components.
- Implementing unit tests.

This project was generated using Angular CLI version 12.2.4 and an ASP.NET Core Web API.

## Repository

The project repository can be cloned from:

- [https://github.com/imon66/Todo-App.git](https://github.com/imon66/Todo-App.git)

## How to Run This App Locally

To run this application locally, ensure you have the following installed:

- **Node.js**
- **.NET Core SDK**
- **SQL Server or SQLClient**

### Clone the Repository

1. Open your terminal and run the following command:
   ```bash
   git clone https://github.com/imon66/Todo-App.git
   ```
2. Navigate to the project folder:
   ```bash
   cd todo-angular-.netcore-main
   ```

### Backend Setup

1. Navigate to the backend folder:
   ```bash
   cd TodoAPI
   ```
2. Run the backend using .NET Core:
   ```bash
   dotnet run
   ```
3. Once successful, the API will be available at:
   - [http://localhost:5000/api/todoitems](http://localhost:5000/api/todoitems)

### Frontend Setup

1. Open a new terminal window and navigate to the frontend folder:
   ```bash
   cd TodoApp
   ```
2. Install dependencies (if not already installed):
   ```bash
   npm install
   ```
3. Run the Angular application:
   ```bash
   ng serve
   ```
4. Access the application at:
   - [http://localhost:4200/](http://localhost:4200/)

---

Enjoy managing your todos with this Angular + ASP.NET Core application!

