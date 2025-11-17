# CoTasker

CoTasker is a full-stack web application for collaborative task and event management. It allows users to sign up, create and manage events, assign tasks, and collaborate efficiently.

## Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Backend Setup](#backend-setup)
  - [Frontend Setup](#frontend-setup)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

---

## Features

- User authentication and registration
- Event creation and management
- Task assignment and tracking
- Responsive dashboard
- Modern UI with Tailwind CSS
- RESTful API backend with Node.js and Express

## Project Structure

```
CoTasker/
├── backend/
│   ├── modules/
│   ├── routes/
│   ├── server.js
│   └── package.json
├── frontend/
│   ├── public/
│   ├── src/
│   ├── index.html
│   └── package.json
└── Cotasker_recordings/
```

## Tech Stack

- **Frontend:** React, Vite, Tailwind CSS
- **Backend:** Node.js, Express, MongoDB (with Mongoose)
- **Other:** ESLint, PostCSS

## Getting Started

### Backend Setup

1. Navigate to the backend folder:
   ```sh
   cd backend
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Set up your MongoDB connection string in `server.js` or use environment variables.

4. Start the backend server:
   ```sh
   npm start
   ```
   The backend will run on `http://localhost:5000` by default.

### Frontend Setup

1. Navigate to the frontend folder:
   ```sh
   cd frontend
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Start the frontend development server:
   ```sh
   npm run dev
   ```
   The frontend will run on `http://localhost:5173` by default.

## Usage

- Open your browser and go to `http://localhost:5173` to access the CoTasker app.
- Register a new account or log in.
- Create events, add tasks, and manage your dashboard.

## Folder Structure

### Backend

- `modules/` - Mongoose schemas for users, events, and tasks
- `routes/` - Express route handlers for users, events, and tasks
- `server.js` - Main server entry point

### Frontend

- `src/componentsDashboard/` - Dashboard UI components (Eventbar, Eventform, etc.)
- `src/componentsSignUp/` - Signup page components
- `src/errorMessage/` - Error and success popup components
- `src/pages/` - Main page components (Dashboard, Signup)
- `src/utils/` - Utility functions

### Recordings

- https://drive.google.com/drive/folders/1397aBne55Tl4dMorDWmI0j5V3CXyKNOD?usp=sharing

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements and bug fixes.

## License

This project is licensed under the MIT License.
