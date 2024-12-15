# Banking System Application ✨💸🚀

Welcome to the **Banking System Application**, an intuitive and interactive system that mimics essential banking functionalities! Built with **Java GUI** and powered by **MySQL**, this project provides users with a secure and smooth banking experience. 🔐💳

---

## ✨ Features

1. **User-Friendly Interface** 📝:
   - Interactive GUI for effortless navigation.
   - Styled with Java's Swing framework for a clean and modern look.

2. **Core Banking Operations** 🏦:
   - **Login**: Secure access for authenticated users.
   - **Fast Cash**: Quick withdrawals with predefined options.
   - **Deposit**: Easily add money to your account.
   - **Balance Inquiry**: Check your account balance in real-time.
   - **Mini Statement**: Get an overview of recent transactions.
   - **Transaction History**: A detailed log of account activity.
   - **PIN Change**: Update your ATM PIN securely.

3. **Secure Back-End** 🔒:
   - Data stored in a **MySQL database** with structured schemas.
   - SQL queries for seamless integration of user data.

4. **Error Handling and Feedback** 🔧:
   - Clear prompts for invalid inputs.
   - Instant feedback on successful or failed transactions.

---

## ⚡ Tech Stack

- **Java**: For creating the graphical user interface and managing core functionalities.
- **Swing**: For designing the front-end components.
- **MySQL**: To manage and store all user and transaction data.
- **JDBC**: For connecting the application to the MySQL database.

---

## 🌍 Installation Guide

### Prerequisites
- **Java JDK** (version 8 or later)
- **MySQL Server**
- Any IDE (e.g., IntelliJ, Eclipse, NetBeans)

### Steps
1. Clone this repository to your local system:
   ```bash
   git clone https://github.com/your-repo/banking-system.git
   ```

2. Open the project in your IDE.

3. Set up the database:
   - Create a new MySQL database:
     ```sql
     CREATE DATABASE bank;
     ```
   - Import the provided SQL schema file:
     ```sql
     SOURCE /path/to/schema.sql;
     ```

4. Update the **Conn.java** file with your MySQL credentials.

5. Run the application:
   - Navigate to the `main` method in any class (e.g., `Login.java`) and execute the program.

---

## ⚖️ Functional Overview

### Login 🔑
- Enter your credentials to access the system.
- Designed with secure authentication to protect user accounts.

### Deposit 💳
- Add funds to your account effortlessly.
- Validation checks ensure the accuracy of inputs.

### Withdrawal 💸
- Withdraw money with real-time balance verification.
- Error handling for insufficient funds.

### Transaction History 📊
- View a detailed log of past transactions.
- Organized by date and transaction type.

### PIN Change 🔐
- Update your ATM PIN securely.
- Ensures old PIN verification for added security.

### Mini Statement 🔖
- Get a concise overview of your latest transactions.

---

## 🔧 Project Structure

```
|-- src
|   |-- Login.java           # User authentication
|   |-- Signup2.java         # Additional user details
|   |-- Signup3.java         # Account type and services selection
|   |-- Deposit.java         # Deposit functionality
|   |-- Withdrawl.java       # Withdrawal functionality
|   |-- Conn.java            # Database connection
|-- db
|   |-- schema.sql           # Database schema
|-- assets
|   |-- atm.jpg              # Background image for GUI
|-- README.md                # Project documentation
```

---

## 🚀 Future Enhancements

1. **Add Admin Features** 🔧:
   - Create an admin dashboard to monitor transactions.

2. **Mobile Banking App** 📲:
   - Develop a mobile app to complement the desktop application.

3. **Enhanced Security** ⚡:
   - Implement OTP-based authentication.
   - Encrypt sensitive data before storage.

4. **Notifications** 📢:
   - Email or SMS alerts for every transaction.

---

## 🙌 Contributions
We welcome contributions to make this system even better!
- Fork the repository 🔁
- Create a new branch 📁
- Submit a pull request ⬇

---

## 😎 Authors
- **Your Name** - Sairohith


Feel free to connect on [LinkedIn](https://www.linkedin.com/in/sairohith-tappatla-076378312/) or [GitHub](https://github.com/sairohithtappatla).

---

## 🙏 Acknowledgments
Special thanks to the open-source community and Stack Overflow for guidance and support!

---

## 🎉 Screenshots
Add screenshots of your application here to give users a visual overview of its functionality.

---

Thank you for checking out the **Banking System Application**! Happy coding! ✨🚀

