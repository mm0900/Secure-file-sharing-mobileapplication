# 📦 Secure File Sharing System

A mobile application that enables secure file transfer between verified users using smart contracts and Firebase. It ensures that only authorized receivers can access encrypted files through a unique secure key mechanism.

---

## 🚀 Modules

### 🔐 Sender
- Registers with email, password, name, contact, and location
- Verifies account via email (verification mail sent by app team)
- After login, can:
  - Enter receiver's ID, file description, and location
  - Upload a file and send it securely
  - Automatically generate and send a secure key to the receiver’s email

### 📥 Receiver
- Registers with email, password, name, contact, and a unique Receiver ID  
  _(Format: 1 capital letter + 4 digits, e.g., R1234)_
- After login, can:
  - View encrypted details (date, location, description)
  - Enter the secure key to view and download the file

### 🛡️ Admin
- (To be defined) Could monitor transactions, manage users, and verify activity logs

---

## 💻 Tech Stack

| Component       | Technology Used            |
|----------------|-----------------------------|
| Mobile Frontend | Android Studio + Flutter   |
| Backend Logic   | Smart Contracts (Solidity) |
| Blockchain      | Ganache (Ethereum testnet) |
| Database        | Firebase Firestore         |
| Email System    | Firebase + Custom SMTP     |
| File Storage    | Firebase Storage           |

---

## 🔄 How it Works
[Watch the video](https://vimeo.com/1082106648?share=copy)


1. **Sender Registration** – User signs up and receives an email verification link.
2. **Receiver Registration** – Receiver creates an account with a valid Receiver ID (e.g., R5678).
3. **File Sending** – Sender selects file, fills in details, and submits. A secure key is sent to the receiver's email.
4. **Receiver Access** – Receiver logs in, enters the secure key, and views/downloads the encrypted file.

---

## 📱 Key Features

- Secure key mechanism for access control
- Email verification and notifications
- Blockchain-backed transaction traceability
- Firebase used for real-time database and secure storage
- User-friendly mobile UI built using Flutter

---

## 💬 Community Feedback

Have suggestions or find issues?  
Use the [**Discussions**](https://github.com/mm0900/Secure-file-sharing-mobileapplication/discussions/1) tab to:
- Report bugs 🐛
- Suggest new features 💡
- Ask questions ❓

We appreciate your contribution to making this project better!

---



