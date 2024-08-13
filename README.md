# Online _shop Database 

This repository contains the MySQL database schema and backup for an online store. The database is designed to handle products, users, orders, and other related data necessary for running an e-commerce platform.

## Features

- **Product Management**: Add, update, and delete products with relevant information.
- **Customer Management**: Manage customer data including registration and authentication.
- **Order Processing**: Handle customer orders, including order creation, updates, and status tracking.
- **Discounts and Promotions**: Apply discounts to products.

## Database Structure

The database includes the following tables:

- `products`: Stores product details such as name, description, price, and stock quantity.
- `users`: Stores customer information including  name , password, birth_date
And disabled.
- `orders`: Stores order information, linking customers and products with order details.
- `order_items`: Stores individual items within an order.
- `categories`: Stores the relationship between the product and the category.
- `payments`: Stores payments details such as user_id,check_number, paymentdate
  And  amount.

## Getting Started

### Prerequisites
- MySQL Server installed on your local machine.
- A GitHub account to clone and manage the repository.

### Usage

Once the database is restored, you can start using it with your application. The database is designed to be integrated with any server-side technology that supports MySQL.

### Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. Contributions are welcome!

### Contact

If you have any questions or need further assistance, please contact me at zrstg2021@gmail.com .

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
