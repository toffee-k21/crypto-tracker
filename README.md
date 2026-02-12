# 🚀 Crypto Tracker (Flask + AWS)

A cloud-deployed crypto tracking platform built using **Flask**, **AWS EC2**, **DynamoDB**, and **SNS**.  

This application allows users to:
- Sign up / Sign in securely
- View live crypto prices
- Visualize price data on a dashboard graph
- Receive email alerts using AWS SNS

---

## 🏗️ Architecture

Frontend (Dashboard + Graph)  
⬇  
Flask Backend (REST API + Auth)  
⬇  
AWS DynamoDB (Users + Alerts Storage)  
⬇  
AWS SNS (Email Notifications)  
⬇  
Deployed on AWS EC2  

---

## 🛠️ Tech Stack

- **Backend:** Flask (Python)
- **Database:** AWS DynamoDB
- **Deployment:** AWS EC2
- **Notifications:** AWS SNS
- **Crypto Data:** CoinGecko API
- **Authentication:** Password hashing using Werkzeug
- **Environment Config:** python-dotenv

---

## ✨ Features

- 🔐 Secure authentication (hashed passwords)
- 📊 Interactive dashboard with crypto price graph
- 📩 Email alerts using AWS SNS
- ☁️ Fully deployed on AWS EC2
- 🗄️ NoSQL data storage using DynamoDB
