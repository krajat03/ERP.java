# ERP
Developed a Java-based ERP application to manage retail product inventory and generate customer bills. The system allows users to add, edit, view, and delete product records with batch-level tracking, and supports bill creation, modification, and deletion with real-time stock updates.
Key Features of the Project :-

🔹 Product Inventory Management

-> Add new products with details: product name, batch number, quantity (NOS), MRP, and expiry date.

-> Edit existing product details including quantity, price, and expiry.

-> Delete products from the inventory.

-> View product details with batch-wise tracking.

🔹 Billing System

-> Generate bills for customers by selecting products and specifying quantity.

-> Supports partial stock deduction across multiple batches of the same product.

-> Automatically calculates subtotal and total amount for each bill.

-> Allows bill editing (adjust quantity of items) and reflects changes in stock.

-> Delete existing bills and restore corresponding stock.

🔹 Data Structures & Efficiency
-> Uses HashMap with custom Key class (product name + batch number) for inventory.

-> Stores billing history in another HashMap with unique bill numbers.

-> Ensures fast lookup, insertion, and deletion of data.

🔹 Stock Synchronization

-> Real-time stock update when a bill is generated, edited, or deleted.

-> Prevents overselling by validating available stock before billing.

🔹 User Interface (Console-Based)

-> Menu-driven interface for easy navigation.

-> Step-by-step prompts using Scanner for user input.

-> Clear messages and validations to guide the user.

🔹 Other Highlights

-> Auto-generated bill numbers starting from 1001.

-> Clean, formatted output for generated bills.

-> Proper use of OOP principles (Encapsulation, Custom Classes, Overriding equals() and hashCode()).

