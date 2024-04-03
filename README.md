# Blog Website README

This is a full-stack blog website built using React, Node.js, Express, MongoDB, and JWT authentication.

## Features

- **User Authentication**: JWT (JSON Web Tokens) authentication system for secure user login and registration.
- **Create, Read, Update, Delete (CRUD) Operations**: Users can create, read, update, and delete their blog posts.
- **Pagination**: Paginated view of blog posts for better user experience.
- **Comments**: Users can comment on blog posts.
- **Search**: Search functionality to search for specific blog posts.
- **Responsive Design**: Responsive design to ensure the website looks good on all devices.

## Technologies Used

- **Frontend**:
  - React: JavaScript library for building user interfaces.
  - React Router: Declarative routing for React.
  - Axios: Promise-based HTTP client for making API requests.
  - Bootstrap or Material-UI: UI components and styles.
  
- **Backend**:
  - Node.js: JavaScript runtime environment.
  - Express: Web application framework for Node.js.
  - MongoDB: NoSQL database for storing blog posts and user information.
  - Mongoose: MongoDB object modeling for Node.js.
  - JWT (JSON Web Tokens): Authentication mechanism for securing routes.
  
## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/blog-website.git
   ```

2. Navigate to the backend directory and install dependencies:

   ```bash
   cd backend
   npm install
   ```

3. Start the backend server:

   ```bash
   npm start
   ```

4. Navigate to the frontend directory and install dependencies:

   ```bash
   cd ../frontend
   npm install
   ```

5. Start the frontend server:

   ```bash
   npm start
   ```

6. Open your web browser and visit `http://localhost:3000` to view the blog website.

## Configuration

- **Backend Configuration**:
  - Configure MongoDB connection string in `backend/config/db.js`.
  - Configure JWT secret key in `backend/config/auth.config.js`.
  
- **Frontend Configuration**:
  - API base URL is configured in `frontend/src/services/api.js`. Update it if the backend server is running on a different URL.

## Usage

- Register a new user or login with existing credentials.
- Create new blog posts, edit or delete existing ones.
- View all blog posts, search for specific posts, or paginate through them.
- Comment on blog posts.

## Contributing

Contributions are welcome! Feel free to submit pull requests or open issues for any bugs or feature requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
