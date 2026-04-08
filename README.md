# 🏥 Quantum Secured Healthcare Data Exchange System

## 📌 Project Overview
The **Quantum Secured Healthcare Data Exchange System** is designed to securely store, encrypt, and share sensitive healthcare data using modern cryptographic techniques and blockchain concepts.

Healthcare data is highly sensitive and vulnerable to cyber threats. This project ensures:
- Data confidentiality using encryption
- Data integrity using blockchain
- Secure communication via APIs

---

## 🎯 Objectives
- Protect patient medical records from unauthorized access
- Implement strong encryption using AES algorithm
- Ensure tamper-proof data storage using blockchain
- Provide secure APIs for data exchange
- Build a real-world cybersecurity-based application

---

## 🔐 Key Features
- 🔒 AES Encryption for secure data storage
- 🔑 Secure key generation and handling
- ⛓️ Blockchain-based data integrity verification
- 🌐 REST API for encrypted data transfer
- 🗄️ SQLite database integration
- ⚡ Fast and lightweight system

---

## 🧠 System Architecture
1. User inputs healthcare data  
2. Data is encrypted using AES algorithm  
3. Encrypted data is stored in SQLite database  
4. Blockchain ensures data integrity  
5. API endpoints allow secure retrieval and decryption  

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Framework:** Flask  
- **Database:** SQLite  
- **Libraries:** Cryptography, hashlib, json  
- **Concepts Used:** Encryption, Blockchain, API Development  

---

## 📂 Project Structure


#│── api.py # API endpoints
#│── main.py # Main application logic
#│── blockchain.py # Blockchain implementation
#│── encryption.py # Encryption logic
#│── database.db # SQLite database
#│── dataset/ # Sample healthcare data
#│── README.md

## 🌐 API Endpoints
Method	Endpoint	Description
GET	/data	Fetch encrypted healthcare data
POST	/data	Store encrypted data
GET	/decrypt	Decrypt stored data

## 📊 Dataset Information

This project uses sample healthcare datasets for testing and demonstration
https://www.kaggle.com/datasets/prasad22/healthcare-dataset

## 📈 Future Enhancements
Integration with real hospital systems
Cloud deployment (AWS / Azure)
Quantum cryptography implementation
User authentication & role-based access
Web-based dashboard UI


## 📊 Project Outcome
Successfully implemented secure healthcare data exchange
Demonstrated encryption + blockchain integration
Improved data security and integrity
Built a real-world cybersecurity solution
