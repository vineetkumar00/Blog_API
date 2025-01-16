# Blog_API
Blog API with Express.js and Node.js

Description
This project implements a blog management system using a RESTful API for backend operations and a front-end server to render pages. It includes CRUD functionality for blog posts and uses tools like Express.js, Node.js, and EJS for rendering views. The data is stored in memory, making it ideal for development or demonstration purposes.

Architecture
 Backend API (index.js):
* Hosts the RESTful API on http://localhost:4000.
* Provides endpoints to manage blog posts.
  
Endpoints:
* GET /posts: Fetch all posts.
* GET /posts/:id: Fetch a specific post by ID.
* POST /posts: Create a new post.
* PATCH /posts/:id: Update partial data of a post.
* DELETE /posts/:id: Delete a specific post.
Front-end Server (server.js):

Runs on http://localhost:3000.
Fetches data from the API and renders views using EJS templates.
Routes include:
/: Displays all posts.
/new: Form to create a new post.
/edit/:id: Form to edit an existing post.
Tools and Dependencies:

Express.js: Framework to handle server routes and middleware.
Body-Parser: Middleware to parse incoming request bodies.
Axios: HTTP client for communication between the front-end and API.
EJS: Template engine for rendering dynamic HTML pages.
Features
In-Memory Data Storage:

The posts are stored in a JavaScript array for simplicity.
Includes sample posts for initialization.
Dynamic Rendering:

Pages dynamically render post data using EJS.
Users can create, edit, delete, and view posts via an intuitive interface


Project Overview: Blog API with Express.js and Node.js
Description
This project implements a blog management system using a RESTful API for backend operations and a front-end server to render pages. It includes CRUD functionality for blog posts and uses tools like Express.js, Node.js, and EJS for rendering views. The data is stored in memory, making it ideal for development or demonstration purposes.

Architecture
Backend API (index.js):

Hosts the RESTful API on http://localhost:4000.
Provides endpoints to manage blog posts.
Endpoints:

GET /posts: Fetch all posts.
GET /posts/:id: Fetch a specific post by ID.
POST /posts: Create a new post.
PATCH /posts/:id: Update partial data of a post.
DELETE /posts/:id: Delete a specific post.
Front-end Server (server.js):

Runs on http://localhost:3000.
Fetches data from the API and renders views using EJS templates.
Routes include:
/: Displays all posts.
/new: Form to create a new post.
/edit/:id: Form to edit an existing post.
Tools and Dependencies:

Express.js: Framework to handle server routes and middleware.
Body-Parser: Middleware to parse incoming request bodies.
Axios: HTTP client for communication between the front-end and API.
EJS: Template engine for rendering dynamic HTML pages.
Features
In-Memory Data Storage:

The posts are stored in a JavaScript array for simplicity.
Includes sample posts for initialization.
Dynamic Rendering:

Pages dynamically render post data using EJS.
Users can create, edit, delete, and view posts via an intuitive interface.


API: http://localhost:4000.
Front-end: http://localhost:3000.

Potential Improvements:
* Add persistent database integration (e.g., MongoDB).
* Implement user authentication and authorization.
* Deploy to a cloud platform for public access.
* Enhance the UI with a modern front-end framework like React or Angular.

This project effectively demonstrates a well-structured backend API and its integration with a front-end server for blog management.
