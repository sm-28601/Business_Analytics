# Business Analytics Dashboard

A modern, visually appealing business analytics dashboard built with React, Node.js, and MongoDB.

## Features

- Real-time business metrics and KPIs
- Interactive charts and visualizations
- Order management system
- Expense tracking
- Customer insights
- Real-time notifications
- Dark mode support
- Role-based access control

## Tech Stack

- Frontend: React, Tailwind CSS, Chart.js
- Backend: Node.js, Express
- Database: MongoDB
- Authentication: JWT

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

## Setup Instructions

1. Clone the repository
2. Install dependencies:
   ```bash
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd ../frontend
   npm install
   ```

3. Create a `.env` file in the backend directory with the following variables:
   ```
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   PORT=5000
   ```

4. Start the development servers:
   ```bash
   # Start backend server
   cd backend
   npm run dev

   # Start frontend server
   cd frontend
   npm start
   ```

5. Access the dashboard at `http://localhost:3000`

## Project Structure

```
business-analytics-dashboard/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── hooks/
│   │   └── utils/
│   └── public/
└── backend/
    ├── src/
    │   ├── controllers/
    │   ├── models/
    │   ├── routes/
    │   └── middleware/
    └── config/
``` 