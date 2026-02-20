# ⚽ Turf Management System (MERN Stack)

A full-stack Turf Booking & Management System built using the MERN stack.  
This application allows users to book sports turfs, manage slots, add reviews, and provides an admin dashboard with analytics.

---

## 🚀 Live Demo
( Add your deployed link here )

---

## 📌 Features

### 👤 User Features
- Register & Login (JWT Authentication)
- Browse available turfs
- View turf details (image, amenities, price, rating)
- Select time slot
- Slot limit (Max 3 teams per slot)
- Booking confirmation
- Cancel booking (status-based)
- Add review after booking
- Star rating system
- Google Maps integration

---

### 🛠 Admin Features
- Add / Edit / Delete turfs
- View all bookings
- Cancel bookings
- Dashboard analytics:
  - Total Revenue
  - Monthly Revenue
  - Today Bookings
  - Most Popular Slot
  - Most Booked Turf

---

## ⭐ Review System
- Only users who booked a turf can review
- Duplicate reviews prevented
- Automatic average rating calculation
- Star rating UI

---

## 📊 Analytics
- Revenue calculated using MongoDB aggregation
- Monthly breakdown
- Slot popularity tracking

---

## 🧱 Tech Stack

### Frontend
- React.js
- React Router
- Axios
- React Icons
- Custom CSS

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Role-Based Authorization

---


---

## 🔐 Authentication & Authorization

- JWT-based login system
- Role-based access (User / Admin)
- Protected routes
- Secure API endpoints

---

## 🧠 Business Logic Highlights

- Max 3 bookings per slot
- Prevent overbooking using MongoDB count
- Prevent duplicate reviews
- Auto calculate average rating
- Booking cancellation status handling

---
## 🎯 Future Improvements

- Online payment integration (Razorpay/Stripe)
- Real-time slot updates using Socket.io
- Email notifications
- Mobile responsive enhancement
- Admin review moderation
- Booking history export

---

## 👩‍💻 Author

Harini M  
Full Stack Developer (MERN)

---

## 📜 License

This project is built for educational and portfolio purposes.
