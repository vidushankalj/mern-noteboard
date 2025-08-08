# MERN Noteboard

## Overview

MERN Noteboard is a full-stack web application built using the MERN stack (MongoDB, Express.js, React, Node.js). It allows users to create, read, update, and delete notes, providing a simple and intuitive interface for managing personal or collaborative notes. The application features user authentication, a responsive frontend, and a RESTful API for seamless interaction between the client and server.

## Features

- **User Authentication**: Secure user registration and login using JWT (JSON Web Tokens).
- **CRUD Operations**: Create, read, update, and delete notes with ease.
- **Responsive Design**: A user-friendly interface that works on both desktop and mobile devices.
- **MongoDB Integration**: Persistent storage of user data and notes in a NoSQL database.
- **RESTful API**: Backend API built with Express.js for efficient communication with the frontend.

## Tech Stack

- **MongoDB**: NoSQL database for storing user data and notes.
- **Express.js**: Backend framework for building the RESTful API.
- **React**: Frontend library for creating a dynamic and responsive user interface.
- **Node.js**: Runtime environment for executing server-side JavaScript.
- **JWT**: For secure user authentication.
- **Axios**: For making HTTP requests from the frontend to the backend.
- **Bootstrap/Tailwind CSS**: For styling and responsive design.

## Screenshots
![no_notes]([http://url/to/img.png](https://github.com/vidushankalj/mern-noteboard/blob/main/screenshots/1.png))
![create_note]([http://url/to/img.png](https://github.com/vidushankalj/mern-noteboard/blob/main/screenshots/2.png))
![notes]([http://url/to/img.png](https://github.com/vidushankalj/mern-noteboard/blob/main/screenshots/3.png))

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/vidushankalj/mern-noteboard.git
   cd mern-noteboard
   ```

2. **Install dependencies**:

   - For the backend (`server` folder):
     ```bash
     cd server
     npm install
     ```
   - For the frontend (`client` folder):
     ```bash
     cd client
     npm install
     ```

3. **Set up environment variables**:

   - Create a `.env` file in the `server` folder with the following:
     ```
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret_key
     PORT=5000
     ```

4. **Run the application**:

   - Start the backend server:
     ```bash
     cd server
     npm start
     ```
   - Start the frontend development server:
     ```bash
     cd client
     npm start
     ```

5. **Access the application**:
   - Open your browser and navigate to `http://localhost:3000` for the frontend.
   - The backend API will be available at `http://localhost:5000`.

## Lessons Learned

While building the MERN Noteboard, I gained valuable insights and skills, including:

- **Full-Stack Development**: Learned how to integrate a frontend (React) with a backend (Node.js/Express) and connect it to a MongoDB database, creating a cohesive full-stack application.
- **RESTful API Design**: Gained experience in designing and implementing RESTful APIs, including handling HTTP methods (GET, POST, PUT, DELETE) and structuring endpoints.
- **User Authentication**: Implemented JWT-based authentication, understanding token generation, verification, and securing routes.
- **State Management in React**: Explored React hooks (e.g., `useState`, `useEffect`) for managing state and handling side effects in the frontend.
- **MongoDB and Mongoose**: Learned how to model data using Mongoose schemas and perform CRUD operations in a NoSQL database.
- **Environment Configuration**: Understood the importance of environment variables for securing sensitive information like database credentials and API keys.
- **Responsive Design**: Used CSS frameworks like Bootstrap or Tailwind CSS to create a responsive and visually appealing interface.
- **Debugging and Error Handling**: Improved skills in debugging full-stack applications, handling errors gracefully, and ensuring a smooth user experience.
- **Version Control**: Practiced using Git and GitHub for version control, including branching, committing, and managing pull requests.

## Future Improvements

- Add real-time collaboration features using WebSockets.
- Implement rich text editing for notes (e.g., using Quill or Draft.js).
- Enhance security with password hashing (bcrypt) and input validation.
- Add note categorization and tagging functionality.
- Deploy the application to a cloud platform like Heroku or Vercel.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes. Ensure your code follows the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, feel free to reach out:

- GitHub: [vidushankalj](https://github.com/vidushankalj)
- Email: vidulakshanlj@gmail.com
