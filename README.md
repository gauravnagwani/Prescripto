# 🏥 Prescripto - Doctor Appointment Booking System

Prescripto is a full-stack Doctor Appointment Booking System built using the MERN Stack. The platform enables patients to book appointments online, doctors to manage appointments and profiles, and administrators to manage doctors and platform operations through dedicated dashboards.

## 🚀 Live Demo

🌐 **Frontend Application:**
https://prescripto-gaurav.vercel.app

---

## ✨ Features

### 👤 Patient Module

* User Registration & Login
* JWT Authentication
* Browse Doctors by Specialty
* Book Appointments
* Cancel Appointments
* View Appointment History
* Update Profile Information

### 👨‍⚕️ Doctor Module

* Doctor Login
* Doctor Dashboard
* Manage Appointments
* View Earnings Information
* Update Doctor Profile

### 🛠️ Admin Module

* Admin Login
* Dashboard Overview
* Add New Doctors
* Manage Doctor Profiles
* View and Manage Appointments

### ☁️ Additional Features

* Cloudinary Image Upload Integration
* Responsive User Interface
* MongoDB Database Integration
* Role-Based Authentication
* REST API Architecture
* Razorpay Integration (Configured)

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Tailwind CSS
* Axios
* React Router DOM

### Backend

* Node.js
* Express.js

### Database

* MongoDB Atlas

### Authentication

* JSON Web Token (JWT)

### Cloud Storage

* Cloudinary

### Deployment

* Vercel
* Render

---

## 📷 Screenshots

| Home Page                                                                                                | Doctors Page                                                                                             |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| <img src="https://github.com/user-attachments/assets/b2118d52-02bd-4d09-933a-1c6f691b878b" width="100%"> | <img src="https://github.com/user-attachments/assets/80991bd5-635e-4399-82a1-5ad88732cab8" width="100%"> |

| Appointment Booking                                                                                      | Add Doctor                                                                                               |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| <img src="https://github.com/user-attachments/assets/96bdbb09-11ab-4b70-94b6-1430a97b5831" width="100%"> | <img src="https://github.com/user-attachments/assets/3874d4e5-2b71-4788-b760-5e629b9bccf6" width="100%"> |

| Doctor Dashboard                                                                                         | Admin Dashboard                                                                                          |
| -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| <img src="https://github.com/user-attachments/assets/2565f63d-3708-49dd-a307-3311d753305c" width="100%"> | <img src="https://github.com/user-attachments/assets/16c17406-20fd-44a2-86e7-798d1405d0e3" width="100%"> |

---

## 📁 Project Structure

```bash
Prescripto/
├── frontend/
├── admin/
├── backend/
└── README.md
```

---

## ⚙️ Installation & Setup

### Clone Repository

```bash
git clone <repository-url>
cd Prescripto
```

---

## 🔧 Backend Setup

```bash
cd backend
npm install
```

Create `.env` file:

```env
ADMIN_EMAIL=your_admin_email
ADMIN_PASSWORD=your_admin_password

CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name

CURRENCY=INR

JWT_SECRET=your_jwt_secret

MONGODB_URI=your_mongodb_connection_string

RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
```

Run backend:

```bash
npm run server
```

---

## 💻 Frontend Setup

```bash
cd frontend
npm install
```

Create `.env`:

```env
VITE_BACKEND_URL=http://localhost:4000
```

Run frontend:

```bash
npm run dev
```

---

## 🛡️ Admin Panel Setup

```bash
cd admin
npm install
```

Create `.env`:

```env
VITE_BACKEND_URL=http://localhost:4000
```

Run admin panel:

```bash
npm run dev
```

---

## 🔐 Authentication Levels

### Patient

* Register/Login
* Book Appointments
* Manage Profile
* Manage Appointments

### Doctor

* Login
* Manage Appointments
* View Dashboard
* Update Profile

### Admin

* Login
* Add Doctors
* Manage Doctors
* Manage Appointments
* View Dashboard Analytics

---

## 🔮 Future Enhancements

* Complete Razorpay Payment Flow
* Email Notifications
* Appointment Reminders
* Video Consultation
* Prescription Management
* Medical Record Storage
* Multi-Hospital Support

---

## 🙏 Acknowledgement

This project was developed while following the Prescripto MERN Stack tutorial by GreatStack and was independently configured, deployed, tested, and customized for learning and portfolio purposes.
