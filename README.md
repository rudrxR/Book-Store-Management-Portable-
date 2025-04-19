

# 📚 Book Store Management System

A modern and responsive **Book Store Management System** built using **Java Swing** and **SQLite**. This desktop application is designed for bookstore administrators to manage inventory efficiently with a clean UI and smooth functionality.

---

## 🚀 Features

- 🧾 **Admin Login System** with secure validation
- 📦 **Inventory Management** – Add, update, delete, and search books
- 📚 **Book Categorization** – Based on category and genre
- 💰 **Price and Quantity Handling**
- 🔎 **Dynamic Search** with filters
- 🧠 **Auto-Fill Fields** by selecting Book ID
- 💡 **Responsive GUI** using `CardLayout` and modern design principles
- 🎨 **Custom Buttons & Dialog Boxes** with curved UI
- 🛠 **Database Integration** using `SQLite`
- 🔐 **Error Handling** for invalid entries and duplicates

---

## 🛠 Technologies Used

| Technology        | Description                            |
|------------------|----------------------------------------|
| Java Swing        | GUI development                       |
| SQLite            | Lightweight database                   |
| JDBC              | Java Database Connectivity             |
| CardLayout        | For responsive UI navigation           |
| IntelliJ | IDE for development and testing                 |

---

## 💻 Screenshots
These are the Screenshots of the GUI: 
- Login Page:

  ![Screenshot 2025-04-13 132100](https://github.com/user-attachments/assets/69a58458-45ef-41dd-a544-e7df27fe6c9f)
- Dashboard:

  ![Screenshot 2025-04-11 194515](https://github.com/user-attachments/assets/7f009d14-d714-436b-aa70-da4583e32505)
  
- Inventory:

  ![Screenshot 2025-04-13 132553](https://github.com/user-attachments/assets/21251e87-264d-41f9-8419-85d94766b0c5)

- Add Book:

  ![Screenshot 2025-04-13 133003](https://github.com/user-attachments/assets/536b594c-e495-4005-b5db-5b27aeacd34b)

- Billing:

  ![Screenshot 2025-04-13 133050](https://github.com/user-attachments/assets/7f627f3e-fc2f-4951-bb3d-051a89459fd3)

---

## 📝 How to Run

    1. Clone the repository  
    `git clone https://github.com/rudrx75/bookstore-management-system.git`

    2. Open in your preferred Java IDE (IntelliJ Idea Community Edition)

    3. Run `LoginPage.java` as the entry point

    4. Make sure `SQLite` is connected and `bookstore.db` exists in the path

---

## 📂 Database Schema
    CREATE TABLE books (
        book_id TEXT PRIMARY KEY,
        name TEXT NOT NULL,
        publisher TEXT,
        author TEXT,
        quantity INTEGER,
        price REAL,
        category TEXT,
        genre TEXT
    );



## 📚 References

- [Java Swing Documentation](https://docs.oracle.com/javase/tutorial/uiswing/)
- [SQLite Java Integration](https://www.sqlitetutorial.net/sqlite-java/)
- [Java JDBC Guide](https://www.javatpoint.com/java-jdbc)

---

## ✨ Future Enhancements

- 📊 Add **Sales and Billing Module** to handle transactions and generate bills
- 📈 Generate **Reports and Analytics** for inventory and sales insights
- ☁️ Integrate **Cloud Database** (like MySQL on Oracle/AWS) for remote access
- 👥 Add **User Role System** (Admin vs. Staff) for controlled access
- 🛒 Implement **Order Management** for future stock tracking
- 🔔 Add **Notification System** for low stock alerts

---

## 🧑‍💻 Author

**Rudraksh Ramekar**  
_B.E. Computer Science & Engineering (Data Science)_
