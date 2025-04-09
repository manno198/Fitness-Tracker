#  Fitness Tracker Web Application

## 📌 Project Overview

The **Fitness Tracker** is a web-based application that enables users to log and monitor their workouts and meals. The app provides input forms for activity logging, visual statistics for fitness trends, and secure user authentication. It combines modern front-end and back-end technologies to deliver a smooth and interactive experience.

---

## 👨‍💻 Project Team

- **Harshita Singh (Team Lead)** – Backend Development  
- Dhanashree Chandratre – Front-end Development  
- Jiya Sahu – Front-end Development  
- Apparao Tiruveedula – Backend Development  
- Jaya Raju Kolli – Backend Development  
- Manikant Raj – Backend Development  
- Mayank Srivastava – Backend Development  

---

## Project Technologies

### 🔹 Frontend
- **HTML** – Webpage structure including login, registration, and tracking forms  
- **CSS** – Styling and responsive layout  
- **JavaScript** – Form validation, interactivity, and chart generation  

### 🔹 Backend
- **Node.js & Express.js** – Handles APIs and server-side logic  
- **MongoDB (Mongoose)** – Database for user and activity records  
- **JWT Authentication** – Secures user login and sessions  

---

## Project Setup

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   - Rename `.env.example` to `.env`
   - Fill in your MongoDB URI and JWT secret
4. Start the server:
   ```bash
   npm start
   ```

###  Frontend Setup
- Open `index.html` in your browser  
- Ensure the backend server is running to enable API functionality

---

##  Features

###  User Authentication
- Secure login & registration via `userRoutes.js`  
- JWT-based session handling

### sxx Activity Logging
- Track workouts and meals (type, duration, calories)  
- Managed through `activityRoutes.js`

###  Data Storage
- MongoDB handles all persistent data  
- `db.js` manages database connection

### Fitness Progress Charts
- JavaScript dynamically renders progress statistics using Chart.js

### Error Handling
- Robust server-side validation and error messages for failed requests

---

## Resources

- [Express.js Documentation](https://expressjs.com/)  
- [MongoDB Mongoose](https://mongoosejs.com/docs/)  
- [JWT Authentication](https://jwt.io/)  
- [Chart.js for Charts](https://www.chartjs.org/)  

---

## Risks

- **Security**: Ensuring safe JWT storage and transfer  
- **Cross-Browser Compatibility**: Testing across multiple browsers  
- **Data Safety**: Backups for stored user data

---

## 🚀 Future Improvements

- Enhance user profiles with more fitness goals  
- Add advanced analytics and personalized suggestions  
- Include more diverse workout categories

