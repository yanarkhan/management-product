# Management Product

The **Management Product** is a Java-based desktop application developed in NetBeans IDE. This application allows users to manage product data through a graphical interface, providing functionality for creating, reading, updating, and deleting (CRUD) product information stored in a MySQL database.

## Features

- **CRUD Operations**: Manage products by adding, viewing, updating, and deleting records.
- **Java Swing GUI**: User-friendly graphical interface for interacting with the product data.
- **MySQL Database Integration**: Persistent data storage using MySQL.
- **Search and Filter**: Search products by various criteria.

## Technologies Used

- **Java** (JDK)
- **NetBeans IDE**
- **Java Swing** (for GUI)
- **MySQL** (for database)
- **JDBC** (Java Database Connectivity) for database communication

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yanarkhan/management-product.git
   ```

2. **Set up the MySQL database**:

   - Create a new MySQL database.
   - Use the `schema.sql` file located in the `resources/db/` directory to create the necessary tables.

3. **Configure the database connection**:

   - Update the database connection details in the `ProductDAO.java` file with your MySQL credentials.

4. **Open the project in NetBeans**:

   - Open NetBeans IDE.
   - Go to `File > Open Project` and select the `management-product` folder.

5. **Run the project**:
   - In NetBeans, right-click on the project and select `Run`.

## Usage

- **Add Product**: Use the form to enter product details and save them to the database.
- **View Products**: Display all products in the database.
- **Update Product**: Select a product and update its details.
- **Delete Product**: Remove a product from the database.

## Contribution

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
