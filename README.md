

# MERN Stack Doctor Appointment Application

## Description

This is a full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) for managing doctor appointments. The application allows users to schedule, view, and cancel appointments with doctors.

## Features

- User authentication: Users can sign up, log in, and log out securely.
- Appointment scheduling: Users can schedule appointments with available doctors.
- View appointments: Users can view their scheduled appointments.
- Cancel appointments: Users can cancel appointments they have previously scheduled.

## Technologies Used

- MongoDB: NoSQL database used for storing appointment data.
- Express.js: Web application framework used for building the backend API.
- React.js: JavaScript library used for building the frontend user interface.
- Node.js: JavaScript runtime environment used for running the server-side code.
- Bootstrap: Frontend framework used for styling the user interface.
- JWT (JSON Web Tokens): Used for authentication and authorization.
- Axios: Promise-based HTTP client for making API requests.
- Git and GitHub: Version control and repository hosting for collaborative development.

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Install dependencies for both frontend and backend:

   ```bash
   cd frontend
   npm install
   cd ../backend
   npm install
   ```

3. Set up environment variables:
   
   Create a `.env` file in the backend directory and add the following environment variables:

   ```plaintext
   PORT=5000
   MONGODB_URI=<your-mongodb-uri>
   JWT_SECRET=<your-jwt-secret>
   ```

4. Run the development server:

   Start the backend server:

   ```bash
   cd backend
   npm start
   ```

   Start the frontend development server:

   ```bash
   cd frontend
   npm start
   ```
     To start both at same time
   ```bash
   npm run dev 
   ```
   
6. Open your browser and navigate to `http://localhost:3000` to view the application.

## Usage

- Register a new account or log in with existing credentials.
- Navigate to the appointments section to schedule, view, or cancel appointments.
- Logout from the application when finished.

## Credits

This application was created by Prince.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

