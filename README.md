# Library-management-system
📚 Library Management System (Java)
A desktop-based application developed using Java and NetBeans IDE for efficiently managing the day-to-day operations of a library. It supports book inventory management, user handling, and book issuance tracking.

🚀 Features
📖 Book Management: Add, update, and delete book records.

👤 Issuer Management: Register and manage book issuers.

📅 Issue/Return Books: Track which user has borrowed which book and when.

🔍 Search Functionality: Easily search for books or users.

🛠 Admin Interface: GUI designed using Java Swing.

📁 Data Storage: Uses file-based or embedded storage (NetBeans-style).

🧰 Technologies Used
Java (Swing) for GUI

NetBeans IDE project structure

JDK 8+

File-based/Serialized object storage

🗂 Project Structure
css
Copy
Edit
📁 src/
   └── librarymanagementsystem/
       ├── Addbooks.java
       ├── AddIssuer.java
       ├── IssueBook.java
       ├── ReturnBook.java
       └── ... other forms and logic
📁 nbproject/
📄 build.xml
📄 manifest.mf
▶️ How to Run
Open the project in NetBeans IDE.

Make sure JDK is properly set in NetBeans.

Build the project (Build > Clean and Build).

Run the main file (e.g., LibraryManagementSystem.java or a class with the main GUI launcher).

📝 Notes
Make sure all .form files are intact for GUI editing in NetBeans.

Default data is not connected to an external DB; file-based persistence is used.

📌 Future Improvements
Migrate to database (MySQL or SQLite) for persistence.

Add user login system.

Implement book reservation and overdue fine system.

