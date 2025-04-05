# ✈️ Airline Reservation System (ARS)

A Java-based console application to simulate an Airline Reservation System. It allows **Admins** to initialize flights and view transactions, and **Customers** to view available flights, make reservations with payment processing, and cancel reservations.

---

## 📜 Features

### 👨‍✈️ Admin
- Initialize flights with unique ID, destination, and seat count.
- View all past reservation and cancellation transactions.

### 🧍 Customer
- View available flights.
- Make reservations by choosing a flight, entering details, and processing payment via card or account.
- Cancel reservations using Booking ID and seats.
- Get automatically generated Booking ID.
- Real-time seat updates.

### 💳 Payment Methods
- Card (Requires 16-digit number and 6-digit PIN)
- Account (Requires 10-digit number and 4-digit PIN)


## 🛠️ Technologies Used
- **Java**
- **OOP Concepts**: Classes, Objects, Encapsulation
- **Data Structures**: Arrays
- **I/O**: Scanner

## 📂 Project Structure
```
ARS (Airline Reservation System) 
    ├── ARS.java # Entry point of the system 
```

## ▶️ How to Run

1. **Compile** the project using:
   ```
   javac ARS.java
   ```

2. **Run** the project using:
   ```
   java ARS
   ```

3. **Interact** via console:  
   - Choose role: Admin or Customer  
   - Follow on-screen instructions for booking or admin tasks  

## 🔐 Admin Access

- Password: Admin (case-sensitive)

- Admin can:
    - Initialize flights

    - View all transactions (Reservations and Cancellations)


## 📝 Example Booking Flow
1. Customer selects a flight.

2. Enters name and number of seats.

3. Selects payment method.

4. System validates input and processes payment.

5. Booking is successful, and Booking ID is generated.


## 📌 Notes
- Seats must be available to make a reservation.

- All transactions (both reservations and cancellations) are logged.

- Invalid input is handled with appropriate messages.

## 💡 Future Enhancements
- GUI-based frontend

- Database integration

- User authentication

- Email confirmations

## 🤝 Contribute to ARS  

Feel free to contribute to ARS by creating [**pull requests**](https://github.com/themeetshah/airline-reservation-system/pulls) or [submitting issues](https://github.com/themeetshah/airline-reservation-system/issues).  

---

### 👨‍💻 Developed by [**Meet Shah**](https://github.com/themeetshah)