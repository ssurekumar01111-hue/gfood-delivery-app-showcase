# 🍔 Gfood Delivery App — Production Showcase

A **production-grade food delivery ecosystem** consisting of three interconnected Android applications:  
**Customer App, Restaurant App, and Driver App**.

This repository is a **showcase and documentation project** created to demonstrate **real-world production implementation, customization, security hardening, and deployment experience**.  
👉 **No proprietary source code is included**.

---
## 📖 Exploring This Repository

This is a documentation and showcase repository. No source code is included.

### What's Inside
- Architecture diagrams and system design notes
- Security implementation details
- Firebase configuration references
- Production deployment experience documentation

### Want to Build Something Similar?
The stack used in this project:
| Tool | Purpose |
|------|---------|
| Flutter | Cross-platform mobile apps |
| Firebase Auth | Role-based authentication |
| Cloud Firestore | Real-time database |
| Firebase Functions | Backend logic (Node.js) |
| Razorpay | Payment gateway |
| Google Maps SDK | Location & tracking |

### Live Apps
Try the production apps directly on Google Play (links below).

## 📱 Live Applications (Google Play Store)

- 🚗 **Driver App**  
  https://play.google.com/store/apps/details?id=com.gfood.driver

- 🏪 **Restaurant App**  
  https://play.google.com/store/apps/details?id=com.gfood.restaurant

- 👤 **Customer App**  
  https://play.google.com/store/apps/details?id=com.gfood.customer

---

## 🧩 Platform Overview

Gfood is a **multi-role food delivery platform** designed to support:

- Customer food ordering and payments
- Restaurant order management
- Driver assignment and delivery tracking

All applications communicate through a **shared backend architecture** with **strict role-based access control**.

---

## 🛠 Technology Stack

### 📱 Frontend
- Flutter (Dart)
- Android SDK

### ☁ Backend & Cloud
- Firebase Authentication
- Cloud Firestore
- Firebase Cloud Functions

### 💳 Payments & Location
- Razorpay Payment Gateway
- Cash on Delivery (COD) logic
- Google Maps & Location Services

---

## 🔐 Security & Reliability Focus

Security and stability were treated as **core engineering priorities**:

- Role-based authentication (Customer / Restaurant / Driver)
- Secure Razorpay payment integration
- Cash-on-Delivery verification flows
- Firestore security rules (least-privilege access)
- Input validation and error handling
- Production crash monitoring and performance optimization

📊 **Stability:**  
Achieved approximately **99.9% crash-free sessions** across production releases.

---

## ✨ Key Features

### 👤 Customer App
- Restaurant & menu browsing
- Cart and checkout flow
- Online payment + Cash on Delivery
- Live order tracking
- Order history

### 🏪 Restaurant App
- Order accept / reject workflow
- Real-time order updates
- Menu and availability management

### 🚗 Driver App
- Order assignment lifecycle
- Live location tracking
- Cash collection confirmation
- Delivery status updates
