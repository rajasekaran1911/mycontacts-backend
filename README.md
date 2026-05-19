Contacts Management MERN Application

A full-stack Contacts Management Application built using the MERN stack (MongoDB, Express.js, React.js, Node.js).
The application provides secure user authentication and allows users to manage their personal contacts through a modern React frontend and RESTful backend APIs.


🚀 Features

🔐 Authentication & Authorization

* User Registration
* User Login
* JWT-based Authentication
* Password Hashing using bcrypt
* Protected Routes & APIs

📇 Contact Management

* Create Contacts
* View Contacts
* Update Contacts
* Delete Contacts
* User-specific contact access

🎨 Frontend Features

* React.js frontend using Vite
* Responsive UI
* Navigation using React Router
* Axios API integration
* JWT token storage using localStorage

⚡ Backend Features

* RESTful API architecture
* MongoDB database integration
* Mongoose ODM
* Middleware-based validation
* Centralized error handling
* Async request handling


🛠️ Tech Stack

Frontend

* React.js
* Vite
* Axios
* React Router DOM

Backend

* Node.js
* Express.js

Database

* MongoDB
* Mongoose

Authentication & Security

* JWT (JSON Web Tokens)
* bcrypt

Middleware

* express-async-handler
* Custom Error Handler
* Token Validation Middleware


User Routes

| Method | Endpoint              | Description      |
| ------ | --------------------- | ---------------- |
| POST   | `/api/users/register` | Register User    |
| POST   | `/api/users/login`    | Login User       |
| GET    | `/api/users/current`  | Get Current User |


Contact Routes

| Method | Endpoint            | Description        |
| ------ | ------------------- | ------------------ |
| GET    | `/api/contacts`     | Get All Contacts   |
| POST   | `/api/contacts`     | Create Contact     |
| GET    | `/api/contacts/:id` | Get Single Contact |
| PUT    | `/api/contacts/:id` | Update Contact     |
| DELETE | `/api/contacts/:id` | Delete Contact     |


🔒 Security Features

* Password hashing using bcrypt
* JWT token authentication
* Protected APIs
* User-specific data access
* Environment variable protection


📸 Future Improvements

* Edit Contact UI
* Search & Filter Contacts
* Pagination
* Profile Management
* Dark Mode
* Docker Deployment
* Cloud Deployment (Render + Netlify)

👨‍💻 Author

Rajasekaran J B

* Email: [jbrajasekaran@gmail.com](mailto:jbrajasekaran@gmail.com)
* LinkedIn: [www.linkedin.com/in/rajasekaran-j-b](http://www.linkedin.com/in/rajasekaran-j-b)

⭐ If you like this project

Give this repository a star on GitHub ⭐
