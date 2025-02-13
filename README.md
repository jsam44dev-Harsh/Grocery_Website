# Grocery Website

![Grocery Website](https://via.placeholder.com/1200x600.png?text=Grocery+Website+Preview)

## 📌 Overview
This is a web-based grocery shopping platform that allows users to browse, search, and purchase groceries online. The project is built with modern web technologies to provide a smooth and interactive user experience.

## 🚀 Features
- User authentication (Login/Register)
- Product browsing and filtering
- Add to cart functionality
- Checkout and order summary
- Admin panel for managing products
- Responsive design for all devices

## 🛠 Tech Stack
### Frontend
- React.js
- Tailwind CSS
- Vite

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose ORM)

## 📂 Folder Structure
```
Grocery_Website/
│── client/        # Frontend React application
│── server/        # Backend Node.js server
│── .gitignore
│── README.md
│── package.json
```

## 🔧 Installation & Setup
1. **Clone the repository**
   ```sh
   git clone https://github.com/jsam44dev-Harsh/Grocery_Website.git
   cd Grocery_Website
   ```
2. **Install dependencies**
   - Frontend:
     ```sh
     cd client
     npm install
     npm run dev
     ```
   - Backend:
     ```sh
     cd server
     npm install
     npm start
     ```

3. **Environment Variables**
   Create a `.env` file in the `server` folder and add the necessary environment variables:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   PORT=5000
   ```
