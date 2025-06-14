🧾 Billing System Management (Java + Swing)

## 📌 Overview

This is a GUI-based desktop billing system built using Java Swing, designed for small retail environments like shops or academic purposes. It enables users to input products, compute subtotals, apply tax and discount automatically, and generate a real-time invoice.

## 👨‍💻 Contributors

- **Nishant Choudhary** – 24SCSE1420028  
- **Prithviraj Singh** – 24SCSE1420047  
_Galgotias University_

---

## 🎯 Project Objectives

- Automate billing for small-scale businesses.
- Implement real-time invoice generation.
- Demonstrate Java Swing and OOP concepts in action.

---

## 💡 Features

- Add multiple products with name, price, and quantity.
- Calculate:
  - Subtotal
  - Tax (18%)
  - Discount (10%)
  - Grand Total
- Generate invoice in a text area.
- Input validation and error handling.
- Clean, intuitive, responsive UI.
- Modular, maintainable code.

---

## 🛠️ Technologies Used

| Category           | Tool/Library       |
|-------------------|--------------------|
| Programming       | Java               |
| GUI Framework     | Java Swing         |
| Concepts          | OOP, Event Handling|
| Layout Managers   | GridLayout, FlowLayout, BorderLayout |
| Optional Extension| JDBC (for DB)      |

## 📂 Project Structure

```bash
BillingSystem/
├── Main.java              # Initializes and runs the GUI
├── Product.java           # Product model class
├── BillingService.java    # Handles logic for billing
├── BillingSystemGUI.java  # GUI logic and event handling
└── README.md              # Project documentation


---

🧪 Core Functionalities

Product.java
Stores and manages individual product details.

BillingService.java
Handles logic like:

addProduct(), removeProduct()

calculateTotal(), printBill()

Optional: saveBillToDatabase()


BillingSystemGUI.java

Input fields for product details.

Buttons to add product or generate invoice.

Real-time invoice updates in text area.




---

⚙️ Setup Instructions

1. Install Java (JDK 8 or above).


2. Compile the code:

javac *.java


3. Run the program:

java Main




---

🧪 Validation & Error Handling

Uses try-catch for NumberFormatException.

Ensures no blank, negative, or non-numeric input.

Displays error via JOptionPane.



---

📈 Results

Successful product addition and total calculations.

Tax and discount applied accurately.

Invoice displayed dynamically.

Input validation prevents crashes.



---

🚀 Future Enhancements

Export to PDF or print functionality.

Add database integration via JDBC.

Login authentication for multi-user support.

Stock tracking and inventory management.



---

📚 References

Oracle Java Documentation

GeeksforGeeks – Java

W3Schools – Java Swing

JavaTPoint – Java Tutorial

Stack Overflow

YouTube Tutorials by ProgrammingKnowledge, Telusko, CodeWithHarry



---

🧠 Educational Value

This project is ideal for students learning:

Java Swing

OOP principles

GUI application development

Modular coding and validation
