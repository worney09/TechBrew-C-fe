# TechBrew-C-fe
TechBrew Cafe is a PHP-MySQL web app offering a digital café experience with menu browsing, cart, orders, and membership plans. It features a responsive design, user-friendly interface, and an admin panel for order management—showcasing full-stack development and real-world functionality.
Tools & Technologies Used

- **Frontend:** HTML, Tailwind CSS, JavaScript  
- **Backend:** PHP  
- **Database:** MySQL  
- **Server:** XAMPP  
- **Version Control:** Git + GitHub

---

## 🧩 Key Features

- 🛒 **Cart & Ordering System:** Users can browse the menu, add items to cart, and place orders.
- 📝 **Registration & Feedback:** Users can register and send messages via a contact form.
- 📋 **Admin Panel:** Admins can view, update, or delete orders and user messages.
- 💾 **Database Integration:** Full backend CRUD with MySQL tables like `orders`, `users`, `messages`, and `contact`.

---

## 🔄 Project Flow

### 👤 Customer:
Login/Register ➜ Browse Menu ➜ Add to Cart ➜ Place Order ➜ Send Feedback

shell
Copy
Edit

### 🧑‍💼 Admin:
Login ➜ View Orders ➜ Update/Delete Orders ➜ Read Messages

shell
Copy
Edit

### 🗃️ Database:
MySQL schema with tables:

users

orders

contact

messages

yaml
Copy
Edit

---

## 🖼️ Key Screenshots

> _(Add images in a `/screenshots` folder if available)_

---

## 🚀 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/techbrew-cafe.git
Place the project in your htdocs folder (for XAMPP):

makefile
Copy
Edit
C:\xampp\htdocs\techbrew-cafe
Start Apache and MySQL in XAMPP.

Import the SQL file:

Open phpMyAdmin

Create a database named techbrew

Import the provided .sql file

Open the project in your browser:

arduino
Copy
Edit
http://localhost/techbrew-cafe/home.php
📁 Project Structure
arduino
Copy
Edit
techbrew-cafe/
├── home.php
├── menu.php
├── register.php
├── contact.php
├── admin/
│   └── view_orders.php
├── css/
├── js/
├── images/
└── techbrew.sql
✅ Conclusion
TechBrew Cafe demonstrates how front-end and back-end technologies integrate through a database to create responsive, real-world e-commerce solutions. It helped reinforce skills in web development, UI/UX, and server-side logic.

📄 License
This project is intended for educational purposes.
