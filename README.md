# Inventory and Sales Analytics System for a Retail Store 📦
Build a relational database to simulate the backend for a retail store. The system manages products, inventory, customers, sales transactions, suppliers, and sales reports. I’ll also create complex queries to perform business analysis such as finding the best-selling items, identifying low stock, and calculating monthly revenue.

## Core Tables:
- products (product_id, name, category, price, stock_quantity)
- customers (customer_id, name, email, phone, registration_date)
- suppliers (supplier_id, name, contact_info)
- purchases (purchase_id, supplier_id, product_id, quantity, purchase_date)
- sales (sale_id, customer_id, sale_date, total_amount)
- sale_items (sale_id, product_id, quantity, unit_price)

