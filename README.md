# 🌾 Farm-to-Fork Traceability System

An end-to-end **Farm-to-Fork Traceability Platform** that tracks agricultural products from **farmer → batch → events → orders → shipment**, with support for **IoT data** and **blockchain integration**.

---

## 🛠 Tech Stack

* **Backend:** Node.js, Express
* **Frontend:** React (Vite)
* **Database:** MariaDB / MySQL
* **Blockchain:** Rust (Cargo)
* **Package Manager:** npm

---

## 📁 Project Structure

```
/main-project
 ├── server
 ├── client
 ├── config
 │    └── db.js
 └── blockchain   (separate branch)
```

---

## 🚀 How to Run the Project

### 1️⃣ Start the Backend Server

1. Move to the **main project folder**
2. Install dependencies (if not installed):

   ```bash
   npm install
   ```
3. Start the backend server:

   ```bash
   npm start
   ```

---

### 2️⃣ Start the Frontend (Client)

1. Navigate to the **client folder**:

   ```bash
   cd client
   ```
2. Install dependencies:

   ```bash
   npm install
   ```
3. Run the development server:

   ```bash
   npm run dev
   ```

---

## 🗄 Database Configuration

Database credentials are located in:

```
config/db.js
```

### Default Credentials:

```js
user: 'root',
password: '1122'
```

🔹 You can **change these credentials** according to your local database setup.

Make sure:

* MariaDB / MySQL is running
* The database exists before starting the server

---

## ⛓ Blockchain Setup

The blockchain module is located in the **Blockchain branch**.

### Steps to Run Blockchain:

1. Switch to the **Blockchain branch**
2. Move to the blockchain project folder
3. Run:

   ```bash
   cargo run
   ```

📌 Ensure **Rust and Cargo** are installed on your system.

---

## ✅ Key Features

* Product and batch traceability
* Parent–child batch genealogy
* Event-based history tracking
* Media proof for quality checks
* IoT raw data storage
* Blockchain transaction linking
* Multi-item order support

---

## 📌 Notes

* UUIDs are generated at the application level
* Blockchain integration is optional but recommended
* Designed for scalability and audit transparency


