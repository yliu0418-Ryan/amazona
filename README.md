# AMAZONA

# Lessons

1. Introduction
2. Install Tools
3. Create React App
4. Create Git Repository
5. List Products
   1. create products array
   2. add product images
   3. render products
   4. style products
6. Add routing
   1. npm i react-router-dom
   2. create route for home screen
   3. create router for product screen
7. Create Node.JS Server
   1. run npm init in root foldeer
   2. update package.json set type: moudle
   3. Add.js to imports
   4. npm install express
   5. create server.js
   6. add start command as node backend/server.js
   7. require express
   8. create route for / return backend is ready
   9. move products.js from frontend to backend
   10. create route for /api/products
   11. return products
   12. run npm start
8. Fetch Products From Backend
   1. set proxy in package.json
   2. npm install axios
   3. use state hook
   4. use effect hook
   5. use reducer hook
9. Manage State By Reducer Hook
   1. define reducer
   2. update fetch data
   3. get state from usReducer
10. Add bootstrap UI Framework
    1. npm install react-bootstrap bootstrap
    2. update App.js
11. Create Product Details Screen
    1. fetch product from backend
    2. create 3 columns for image, info and action
12. Create Loading and Message Component
    1. create loading component
    2. use spinner component
    3. create message component
    4. create util.js to define getError function
13. Implement Add To Cart
    1. create React Context
    2. define reducer
    3. create store provider
    4. implement add to cart button click handler
14. Complete Add To Cart
    1. check exist item in the cart
    2. check count in stock in backend
15. Create Cart Screen
    1. create 2 columns
    2. display items list
    3. create action colum
16. Complete Cart Screen
    1. click handler for inc/dec item
    2. click handler for remove item
    3. click handler for checkout
