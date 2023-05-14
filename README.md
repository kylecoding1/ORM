
# E-Commerce Backend

## clip of it working [2023-05-14 14-55-54.zip](https://github.com/kylecoding1/ORM/files/11473030/2023-05-14.14-55-54.zip)

## Description

This is an E-commerce backend application which provides a comprehensive set of RESTful API endpoints to Create, Read, Update, and Delete (CRUD) products, categories, and tags in an E-commerce platform.

## Installation

To install the necessary dependencies, run the following command:

```bash
npm install


2 / 2

bash
Copy code
# E-Commerce Backend

## Description

This is an E-commerce backend application which provides a comprehensive set of RESTful API endpoints to Create, Read, Update, and Delete (CRUD) products, categories, and tags in an E-commerce platform.

## Installation

To install the necessary dependencies, run the following command:

```bash
npm install

## Usage
Set up your MySQL database by creating a .env file in the root directory of the project and providing your database credentials:

DB_NAME=your_database_name
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password

Create the database schema and seed it with sample data by running the following commands:
npm run schema
npm run seed

Start the server by running the following command:

npm start

## API Endpoints
The following API endpoints are available:

Categories
GET all categories: /api/categories
GET a category by ID: /api/categories/:id
POST a new category: /api/categories
PUT (update) a category: /api/categories/:id
DELETE a category: /api/categories/:id
Products
GET all products: /api/products
GET a product by ID: /api/products/:id
POST a new product: /api/products
PUT (update) a product: /api/products/:id
DELETE a product: /api/products/:id
Tags
GET all tags: /api/tags
GET a tag by ID: /api/tags/:id
POST a new tag: /api/tags
PUT (update) a tag: /api/tags/:id
DELETE a tag: /api/tags/:id
Testing
To test the API endpoints, you can use tools like Insomnia or Postman. Here are some sample requests:

GET all categories: Send a GET request to /api/categories.
GET a category by ID: Send a GET request to /api/categories/:id, replacing :id with the actual ID of a category.
POST a new category: Send a POST request to /api/categories with the category data in the request body.
PUT (update) a category: Send a PUT request to /api/categories/:id, replacing :id with the actual ID of a category, and provide the updated data in the request body.
DELETE a category: Send a DELETE request to /api/categories/:id, replacing :id with the actual ID of a category.
Repeat similar steps for testing products and tags endpoints.

## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to submit a pull request.

## License
This project is licensed under the MIT License.
