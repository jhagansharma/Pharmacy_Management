# Pharmacy_Management
Pharmacy Management System

Overview:

The Pharmacy Management System is a simple yet powerful tool built using Streamlit and SQLite. It helps pharmacy owners manage their inventory, track sales, and get alerts for out-of-stock and expired medicines.


Features:

Inventory Management: Add, update, delete, and search medicines.

Sales Tracking: Record and monitor medicine sales.

Stock Alerts: Get notified about out-of-stock and expiring medicines.

User-Friendly Interface: Powered by Streamlit for easy navigation.



Technologies Used:

Python

Streamlit (for UI)

SQLite (for database management)

Pandas (for data handling)

Streamlit-Option-Menu (for sidebar navigation)



Usage:

Manage Inventory ->

Add Medicine: Enter medicine details (name, price, quantity, expiry date) to add to inventory.

Update Medicine: Modify details of existing medicines.

Delete Medicine: Remove medicines from inventory.

View Inventory ->

View all medicines with details like price, quantity, and expiry date.

Search for specific medicines.

Manage Sales ->

Record sales transactions and update stock levels accordingly.

Alerts ->

Check notifications for out-of-stock, expiring soon, or expired medicines.

Database Structure ->

The application uses an SQLite database (pharmacy.db) with the following tables:

medicines (id, name, price, quantity, expiry_date)

sales (id, medicine_id, quantity)
