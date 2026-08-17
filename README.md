# 🔐 AI-Based UPI Fraud Detection System

An AI-powered web application designed to detect and classify **UPI transactions as Real or Fraudulent** using machine learning and intelligent transaction analysis.

The system provides an interactive dashboard where users can enter transaction details, analyze the transaction, and receive a fraud-risk prediction with relevant insights.

---

## 🚀 Project Overview

Digital payments and UPI transactions have grown rapidly, but this has also increased the risk of fraudulent transactions.

The **AI-Based UPI Fraud Detection System** aims to provide an intelligent solution that analyzes transaction-related information and identifies potentially fraudulent activities.

The application provides:

* 🔐 Secure admin login
* 📊 Interactive fraud detection dashboard
* 💳 UPI transaction analysis
* 🤖 AI/ML-based fraud prediction
* ⚠️ Fraud risk identification
* 📈 Transaction statistics
* 🧠 Intelligent analysis of transaction details
* 📋 Prediction results and recommendations

---

## 🎯 Objectives

The main objectives of this project are:

1. Detect potentially fraudulent UPI transactions.
2. Classify transactions as **Real** or **Fraudulent**.
3. Provide an easy-to-use dashboard for transaction analysis.
4. Reduce the risk of financial fraud through early detection.
5. Use machine learning to identify suspicious transaction patterns.
6. Provide useful insights to help users understand transaction risks.

---

## ✨ Key Features

### 🔐 Admin Login

The system provides an authentication interface for authorized users.

### 💳 Transaction Analysis

Users can enter transaction-related information such as:

* Transaction amount
* Transaction type
* Payment method
* Transaction location
* Device information
* Transaction frequency
* Other relevant transaction parameters

### 🤖 AI-Based Prediction

The system analyzes the provided transaction information and predicts whether the transaction is:

**✅ Real Transaction**

or

**🚨 Potential Fraud**

### 📊 Dashboard

The dashboard provides an overview of transaction analysis with useful statistics and visualizations.

Possible dashboard metrics include:

* Total transactions analyzed
* Fraudulent transactions
* Genuine transactions
* Fraud percentage
* Risk levels
* Recent transaction activity

### ⚠️ Risk Assessment

Transactions can be categorized according to their risk level:

* 🟢 Low Risk
* 🟡 Medium Risk
* 🔴 High Risk

### 📈 Data Visualization

Charts and graphical representations can be used to understand:

* Fraud vs. genuine transactions
* Transaction trends
* Risk distribution
* Transaction amounts
* Fraud patterns

---

## 🏗️ System Architecture

```text
                    ┌─────────────────────┐
                    │       User          │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │     Login Page      │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │     Dashboard       │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Transaction Input   │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Data Preprocessing  │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   ML Model / AI     │
                    │      Analysis       │
                    └──────────┬──────────┘
                               │
                    ┌──────────┴──────────┐
                    ▼                     ▼
             ┌─────────────┐       ┌─────────────┐
             │    REAL     │       │    FRAUD    │
             └─────────────┘       └─────────────┘
                    │                     │
                    └──────────┬──────────┘
                               ▼
                    ┌─────────────────────┐
                    │ Result & Risk Score │
                    └─────────────────────┘
```

---

## 🧠 How It Works

The system follows these major steps:

### Step 1 — User Login

The authorized user enters the required login credentials.

### Step 2 — Transaction Details

The user enters the required UPI transaction information.

### Step 3 — Data Processing

The entered transaction information is processed and converted into a format suitable for analysis.

### Step 4 — AI/ML Analysis

The trained machine learning model analyzes the transaction patterns.

### Step 5 — Fraud Prediction

The system predicts whether the transaction is genuine or potentially fraudulent.

### Step 6 — Risk Result

The dashboard displays the prediction along with the corresponding risk level and relevant information.

---

## 🛠️ Technologies Used

### Frontend

* HTML
* CSS
* JavaScript
* React.js
* Tailwind CSS

### Backend / Application

* Node.js
* API-based architecture

### Artificial Intelligence & Machine Learning

* Python
* Machine Learning
* Scikit-learn
* Data preprocessing
* Classification algorithms

### Database

* SQLite / applicable project database

### Development Tools

* Visual Studio Code
* Git
* GitHub
* npm

---

## 📂 Project Structure

```text
AI-UPI-fraud-detection-system/
│
├── public/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── assets/
│   └── ...
│
├── index.html
├── package.json
├── package-lock.json
├── postcss.config.js
├── tailwind.config.js
├── vite.config.js
├── .gitignore
└── README.md
```

> The exact folder structure may vary depending on the current implementation of the project.

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/mukthanayak2004/AI-UPI-fraud-detection-system.git
```

### 2. Navigate to the Project

```bash
cd AI-UPI-fraud-detection-system
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create a `.env` file locally and add the required API keys or configuration values.

Example:

```env
API_KEY=your_api_key_here
```

**Never upload real API keys or passwords to GitHub.**

### 5. Start the Development Server

```bash
npm run dev
```

The application will then be available through the local development URL shown in your terminal.

---

## 🧪 Example Transactions

### ✅ Example — Genuine Transaction

```text
Transaction Amount: ₹500
Transaction Type: Payment
Location: Bengaluru
Device: Registered Device
Transaction Frequency: Normal

Prediction: REAL
Risk Level: LOW
```

### 🚨 Example — Suspicious Transaction

```text
Transaction Amount: ₹75,000
Transaction Type: Payment
Location: Unknown
Device: New Device
Transaction Frequency: Unusual

Prediction: FRAUD
Risk Level: HIGH
```

> These examples are for demonstration purposes. Actual prediction results depend on the implemented model and input features.

---

## 📊 Expected Output

The system can display a result such as:

```text
-----------------------------------
       TRANSACTION ANALYSIS
-----------------------------------

Prediction     : FRAUD
Risk Level     : HIGH
Risk Score     : 92%
Recommendation : Verify transaction
-----------------------------------
```

---

## 🔮 Future Enhancements

The project can be further enhanced with:

* 📱 Real-time UPI transaction monitoring
* 🧠 Advanced deep learning models
* 🔍 Device fingerprinting
* 🌐 Location-based anomaly detection
* 📊 Advanced fraud analytics
* 🔔 Real-time fraud alerts
* 📧 Email/SMS notifications
* 📈 Advanced prediction reports
* 👥 Multiple user roles
* ☁️ Cloud deployment
* 🔗 Integration with real payment systems
* 🛡️ Continuous model improvement

---

## 🎓 Applications

This system can be useful for:

* Banks
* FinTech companies
* Payment platforms
* Digital wallet providers
* Financial institutions
* Cybersecurity systems
* Fraud investigation teams

---

## ⚠️ Disclaimer

This project is developed for **educational, academic, and demonstration purposes**.

It should not be considered a production-ready financial fraud prevention system without additional security testing, validated datasets, regulatory compliance, model evaluation, and integration with secure financial infrastructure.

---

## 👩‍💻 Developer

**Muktha Nayak**

BE — Artificial Intelligence & Data Science

GitHub:
https://github.com/mukthanayak2004

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

---

## 📜 License

This project is intended for educational and academic purposes.
