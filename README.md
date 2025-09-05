# E-Commerce Website

This is a full-stack e-commerce web application consisting of three main components:

- **Frontend**: Customer-facing React app built with Vite.
- **Admin**: Admin dashboard for managing products, orders, and users, built with React and Vite.
- **Backend**: Node.js/Express REST API server for handling business logic, authentication, and database operations (MongoDB).

## Features
- Product listing, cart, and order management
- User authentication
- Admin panel for product and order management
- Responsive UI

## Getting Started

### Prerequisites
- Node.js and npm installed
- MongoDB instance (local or cloud)

### 1. Clone the repository
```powershell
git clone https://github.com/majidamin07/E-Commerce-Website.git
cd E-Commerce-Website
```

### 2. Install dependencies
```powershell
cd frontend; npm install
cd ../admin; npm install
cd ../backend; npm install
```

### 3. Configure environment variables
- Create a `.env` file in `backend/` and add your MongoDB URI and other secrets as needed.

### 4. Start the backend server
```powershell
cd backend
npm start
```

### 5. Start the frontend
```powershell
cd ../frontend
npm run dev
```

### 6. Start the admin dashboard
```powershell
cd ../admin
npm run dev
```

## Usage
- Frontend: http://localhost:5173
- Admin: http://localhost:5174 (or as configured)
- Backend: http://localhost:5000 (or as configured)

---

For more details, see the individual README files in each folder.
