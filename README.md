
Webshop Admin Portal and Express API Exercise  
=============================================

In this exercise, we will create a webshop admin portal interface and an Express API to handle CRUD operations for customers, products, and variants. The admin portal will provide a user-friendly interface to manage the webshop's data, while the Express API will serve as the backend to handle requests and interact with the database.

Requirements  
------------

To complete this exercise, you will need:

- Basic knowledge of HTML, CSS, and JavaScript  
- Experience with Express.js and RESTful API development  
- A code editor of your choice  
- A modern web browser  
- Node.js and npm (Node Package Manager) installed on your machine

Getting Started  
---------------

1. Set up a new project directory on your local machine.  
2. Initialize a new Node.js project by running `npm init` in the project directory. Follow the prompts to generate a `package.json` file.  
3. Install the necessary dependencies by running `npm install express` to install Express.js and any other required packages (e.g., `body-parser`, `mongoose` for database connectivity).  
4. Create a new file named `server.js` in the project directory. This will serve as the entry point for your Express server.  
5. Import the required dependencies and set up a basic Express server in the `server.js` file. Set the server to listen on a specified port (e.g., 3000).

Designing the Admin Portal Interface  
------------------------------------

1. Create a new HTML file named `admin.html` in the project directory.  
2. Set up the basic structure of an HTML document by adding the `<!DOCTYPE html>` declaration and the `<html>`, `<head>`, and `<body>` tags.  
3. Link a CSS file to your HTML document by adding the `<link>` tag inside the `<head>` section. Name the CSS file `styles.css`.  
4. Link a JavaScript file to your HTML document by adding the `<script>` tag just before the closing `</body>` tag. Name the JavaScript file `script.js`.  
5. Design the admin portal interface by adding appropriate HTML tags, classes, and IDs to structure and style the content. Consider using forms, tables, input fields, buttons, and other UI components to create a user-friendly interface for managing customers, products, and variants.  
6. Use JavaScript to handle user interactions, form submissions, and making AJAX requests to the Express API endpoints.

Creating the Express API  
------------------------

1. Create a new directory named `routes` in the project directory. This directory will store the Express route handlers for the API endpoints.  
2. Inside the `routes` directory, create separate JavaScript files for handling customer, product, and variant routes (e.g., `customerRoutes.js`, `productRoutes.js`, `variantRoutes.js`).  
3. Import the required dependencies and set up the route handlers for CRUD operations (Create, Read, Update, Delete) for customers, products, and variants. Use Express Router to define the routes and their corresponding functions.  
4. Set up the necessary database connectivity using a package like `mongoose` to interact with a MongoDB database. Configure the database connection in a separate file (e.g., `db.js`) and import it into your route files.  
5. Implement the route handlers for creating, reading, updating, and deleting customers, products, and variants. Use the appropriate HTTP methods (e.g., POST, GET, PUT, DELETE) and endpoint URLs to handle the respective operations.  
6. Test the API endpoints using a tool like Postman or by making requests from the admin portal interface.

Styling the Admin Portal Interface  
----------------------------------

1. Open `styles.css` in your code editor.  
2. Add CSS rules to style the admin portal interface. Use appropriate CSS selectors to target the HTML elements and classes/IDs you created in the `admin.html` file.  
3. Apply styles such as layout, typography, colors, forms, buttons, and any other desired visual elements to create an intuitive and visually appealing admin portal interface.

Running the Application  
-----------------------

1. Open a terminal or command prompt and navigate to the project directory.  
2. Start the Express server by running the command `node server.js`.  
3. Open a web browser and navigate to `[http://localhost:3000/admin.html`](http://localhost:3000/admin.html` "http://localhost:3000/admin.html%60") to access the admin portal interface.  
4. Interact with the admin portal, create customers, products, and variants, and verify that the Express API endpoints are functioning correctly by checking the database or using API testing tools.

Remember to handle errors, validate user inputs, and follow best practices for security and data integrity throughout the development process.
