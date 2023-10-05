# course-selling-app-server-2

## Features

- User and Admin Authentication
- User and Admin Registration
- Course Management (Admin)
- Course Purchase (User)
- User Dashboard
- Admin Dashboard

## Technologies Used

- Node.js
- Express.js
- MongoDB (via Mongoose)
- JSON Web Tokens (JWT) for authentication

## API Endpoints
### Admin Routes:

- /admin/signup: Register a new admin.
- /admin/login: Log in as an admin.
- /admin/courses: Create a new course (requires authentication).
- /admin/courses/:courseId: Update a course (requires authentication).
- /admin/courses: Get a list of courses (requires authentication).

### User Routes:

- /users/signup: Register a new user.
- /users/login: Log in as a user.
- /users/courses: Get a list of available courses (requires authentication).
- /users/courses/:courseId: Purchase a course (requires authentication).
- /users/purchasedCourses: Get a list of purchased courses (requires authentication).

## Usage
- This server is designed to be used as the backend for a Course Selling Application. It provides RESTful APIs for user and admin functionalities.
