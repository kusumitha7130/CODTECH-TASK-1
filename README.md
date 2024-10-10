# VEERAVELLY KUSUMITHA
**NAME**: VEERAVELLY KUSUMITHA  
**COMPANY**: CODTECH IT SOLUTIONS PVT. LTD  
**ID**: CT06DS1774  
**DOMAIN**: FULL STACK DEVELOPMENT  
**DURATION**: August 25th to October 10th, 2024


## OVERVIEW OF THE PROJECT


## PROJECT: E-commerce React Shopping Website 


## OBJECTIVES:
Built a e-commerce platform with user authentication,product listings, and a shopping cart. Used React  for the frontend and Express.js  for the backend.Implemented user authentication and authorization. Created product listings and a payment gateway



A comprehensive feature-rich e-commerce website developed as a server-client React application, powered by the **MERN (MongoDB, Express.js, React.js, Node.js) stack**. 
<img height=20px src="https://skillicons.dev/icons?i=react">
<img height=20px src="https://skillicons.dev/icons?i=nodejs">
<img height=20px src="https://skillicons.dev/icons?i=express">
<img height=20px src="https://skillicons.dev/icons?i=mongodb">
<img height=20px src="https://skillicons.dev/icons?i=firebase">
<img height=20px src="https://skillicons.dev/icons?i=js">
This project showcases proficiency in full-stack development, including frontend UI/UX design, backend API development, database management, and integration with external services. <br>

Key Features:
- **dynamic shopping cart**
-  **Interactive review system**
-  **Organized product listings**
- **Paypal payment process**
-  **User authentication and authorization**
-  **User functionalities**, such as order history, and **admin functionalities** such as real-time metrics (registered users, order count, total money orders), creation, editing, and deletion of products.
<br>


##  Frontend Implementation 
The frontend is built using **React.js**, using React features such as hooks (`useState`, `useEffect`), and state management using **Redux**. It includes components and routing to create an interactive user experience.

### Key React features:
1. **React Components**: Utilizes functional components and hooks to manage state and side effects, promoting code reusability and simplification.
2. **Redux State Management**: Manages the global state of the application, including user authentication, product listing, and shopping cart state. Redux Thunk is used for asynchronous operations.
3. **Routing with React Router**: Implements dynamic routing for different parts of the application, including product pages, user login, and the shopping cart.
4. **State Management with useState and useEffect**: Manages local component state and side effects, ensuring components respond to changes in application state efficiently.
5. **Asynchronous Operations with Redux Thunk**: Handles asynchronous logic such as fetching data from the backend.


## Backend Implementation 
The backend of this e-commerce website is built using **Node.js** and **Express.js**, connecting to **MongoDB Atlas** for database management. It includes secure user authentication with **Firebase** and implements API endpoints to handle various functionalities such as product management, user management, and order processing.

### Key Components of the Backend:
1. **Database Management with MongoDB Atlas**: 
   `MongoDB Atlas` is a cloud-based NoSQL database used to manage the application's data efficiently. The database is designed to handle collections for `products, and orders`.

   - **Orders Collection**: Stores order details including items, shipping address, payment method, and user information.
   - **Products Collection**: Contains product information such as name, category, price, stock status, and reviews.


<br>

![mongodb](https://github.com/shanibider/ANASTACIA-MERN-ECOMMERCE/assets/72359805/6e7a4d25-359f-4a7d-9fc6-142608eb803c)
<br>


2. **Express.js for API Development**: 
   `Express.js` is used to create a RESTful API to handle `HTTP requests` and responses, ensuring efficient communication between the frontend and the backend. The API endpoints are 



3. **User Authentication with Firebase**: 
   `Firebase` Authentication is integrated to manage user `sign-up, login, and secure sessions`.



<br>

##### Firebase Authentication:
![firebase](https://github.com/shanibider/ANASTACIA-MERN-ECOMMERCE/assets/72359805/230b5448-2181-4406-ad86-a6ea80d71d6c)

##### Firebase Firestore DB:
![firebase - firestore db](https://github.com/shanibider/ANASTACIA-MERN-ECOMMERCE/assets/72359805/9a613763-0769-4ffb-8401-ecf1637f487b)

<br>



4. **Paypal API** <img align="center" height="40px" src="https://github.com/shanibider/ANASTACIA-MERN-ECOMMERCE-WEBSITE/assets/72359805/1cf2f26b-937f-4eff-950d-a940409e14a9"> -
Using Demo Payment via <img height="20px" align="center" src="https://github.com/shanibider/ANASTACIA-MERN-ECOMMERCE-WEBSITE/assets/72359805/acfd6955-7866-467e-8e13-d168da6bfc00">. To experience the payment process with PayPal, you can use the demo feature. Follow these steps to make a demo payment💰:
  - [x] **Visit the Demo Payment Page**: Navigate to the payment page.
  - [x] **Login with Demo Credentials**: Use the provided demo username and password to access the demo environment.
  - [x] **Initiate Payment**: Enter the demo payment section and select PayPal as the payment method.
  - [x] **Complete Payment**: Follow the instructions to proceed with the demo payment through PayPal.

#### Paypal Sandbox test accounts -
![paypal demo](https://github.com/shanibider/ANASTACIA-MERN-ECOMMERCE/assets/72359805/3f5b4240-98c0-405f-8a4d-8967cbd2bbea)

<br>
 
   
---

# Technologies Used 


### **MERN Stack:**
- [x] **MongoDB:** Efficient and scalable NoSQL database, ensuring robust data storage and retrieval capabilities.
- [x] **Express.js:** Fast and minimalist web framework for Node.js, facilitating the creation of powerful APIs and web applications.
- [x] **React.js:** Dynamic and responsive JavaScript library for building modern and engaging user interfaces, utilizing:
  - [ ] **useState:** React hook for managing state in functional components, enhancing component interactivity and reactivity. 
  - [ ] **useContext:** React hook for accessing and consuming context values across components, facilitating efficient data sharing. 
  - [ ] **useReducer:** React hook for managing complex state logic with reducer functions, offering a more organized approach to state management. 
- [x] **Node.js:** Lightweight and efficient JavaScript runtime environment, enabling scalable and high-performance server-side execution.

### **Firebase:**
- [x] **Authentication:** Firebase authentication services for secure user authentication and authorization management.
- [x] **Real-time Database:** Firebase real-time database for seamless and synchronized data updates across clients in real-time.

### **HTTP/S Protocols:**
- [x] **Axios:** Promise-based HTTP client for making asynchronous requests to the server, enhancing data fetching and manipulation.
- [x] **AJAX:** Asynchronous JavaScript and XML for making seamless requests to the server without refreshing the entire page.
- [x] **Fetch API:** Modern browser API for fetching resources asynchronously across the network, improving data retrieval efficiency.

### **Payment Processing:**
- [x] **PayPal API:** Integration of PayPal API for secure and reliable payment processing, ensuring seamless transactions for users.

### **Frontend Development:**
- [x] **HTML, CSS, JavaScript:** Foundational technologies for building the frontend interface, providing structure, style, and interactivity to web applications.
- [x] **Bootstrap:** Frontend framework for developing responsive and mobile-first web projects, streamlining the design and layout process and ensuring compatibility across various devices. 
<br>



# Key Features 
- [x]  **Home Page:** 
  - Lists products to browse and explore.

- [x]  **Detailed Product View:** 
  - Provides in-depth information about a selected product.

- [x]  **Product Categories:** 
  - Categorizes products for easy navigation.

- [x]  **Shopping Cart:** 
  - Allows users to add and manage items in their cart.

- [x]  **Order Processing with PayPal:** 
  - Securely handles payment processing using the PayPal API for demo purposes.

- [x]  **Secure User Registration and Login:** 
  - Ensures a safe and secure user authentication system.

- [x]  **Admin Functionalities:** 
  - Manages 'Products' and 'Orders' lists
  - Features a dashboard displaying real-time metrics: registered users, order count, and financial performance through total money orders.
  - Enables the creation, editing, and deletion of products.

- [x]  **User Functionalities:** 
  - Accesses order history.
  - Edits user profile.

- [x]  **About The Team Page:** 
  - Provides information about the development team.   
<br>




<br>






## Ecommerce Website Preview :
### Demo Website

 Demo : 

<img src="https://user-images.githubusercontent.com/72359805/230923394-09e38358-b620-4bc1-a3f0-f2620eb510c0.mp4" alt=" Click here for Demo" width="300">



###### Home Page
![home](https://user-images.githubusercontent.com/72359805/230922135-b29b6c60-afd5-48ec-9fc4-d5e2e44a085a.PNG)

###### Product out of stock alert

![out of stock alert](https://github.com/shanibider/Anastacia-Ecommerce-React-Website/assets/72359805/58f0ea96-a220-47e3-a682-9e683fd04557)

###### Detailed Product View
![product](https://user-images.githubusercontent.com/72359805/230922485-2206ef84-98bf-42fa-8365-c2e0c192ade0.PNG)

###### Shopping Cart 
![cart](https://user-images.githubusercontent.com/72359805/230922510-57753e47-0df0-4e5e-8fe4-a7bbb61e810b.PNG)

###### Preview order  
![place order](https://user-images.githubusercontent.com/72359805/230922503-9a7df6f3-7203-43ac-87a8-a6453476bcde.PNG)


<br>

### Place an order via PayPal API:  

###### Place order  
![place order paypal](https://github.com/shanibider/Anastacia-Ecommerce-React-Website/assets/72359805/37f789f4-a0e5-4870-b250-89228553b3dc)

###### Checkout steps - shipping
![shipping](https://github.com/shanibider/Anastacia-Ecommerce-React-Website/assets/72359805/7986aa25-75fd-4cfa-b234-3e7e0858f897)

###### Checkout steps - payment method
![payment method](https://github.com/shanibider/Anastacia-Ecommerce-React-Website/assets/72359805/6207865a-b308-41b7-bb26-7ca75bcbe39c)

###### Place an order with demo user via PayPal
![place order paypal  demo 2](https://github.com/shanibider/Anastacia-Ecommerce-React-Website/assets/72359805/e98e741a-9e6a-44fb-bc25-02ff4215987b)

###### Paid order
![place order paypal  demo 3](https://github.com/shanibider/Anastacia-Ecommerce-React-Website/assets/72359805/86d4ae07-2cd3-474f-a51d-7e77d8c11cff)


<br>

## User functionality:

###### User order history
![order history](https://user-images.githubusercontent.com/72359805/230922850-bf35dce7-eaea-4ff2-9d95-741a9b0edb77.PNG)

###### User edit profile
![edit profile](https://github.com/shanibider/Anastacia-Ecommerce-React-Website/assets/72359805/422c48d0-a035-4e0c-91b0-711b9918a2b0)

<br>

## Admin functionality:

###### Admin dashboard displaying real-time metrics: registered users, order count, and financial performance through total money orders
![Admin info](https://user-images.githubusercontent.com/72359805/230922856-8218eadd-3c44-4689-8710-5757060e9177.PNG)

###### Products list
![proudcts list](https://user-images.githubusercontent.com/72359805/230922896-699796f4-1268-441f-b5c1-417273d1aec9.PNG)

######  Edit product 
![edit product](https://user-images.githubusercontent.com/72359805/230922907-bb0abeb0-6cad-42d3-9629-238447091dbd.PNG)

######  All users orders list
![orders list](https://user-images.githubusercontent.com/72359805/230922948-31ea760e-cccf-4d6c-b4ce-9b9b5d964419.PNG)

<br> 

###### Search bar
![search](https://user-images.githubusercontent.com/72359805/230922982-83d66ae1-cc6d-4cca-b5be-b21c1f7c7628.PNG)


###### about us page
![about us](https://user-images.githubusercontent.com/72359805/230923017-44b75026-def1-40bf-af5f-7d8f2d76ee1b.PNG)

![about us2](https://user-images.githubusercontent.com/72359805/230923021-ee53f35c-7676-485a-93a7-5f53cb9eaec9.PNG)

###### Spinner Component showing the loading state

![loadingBox component](https://github.com/shanibider/Anastacia-Ecommerce-React-Website/assets/72359805/51546c31-6154-4802-9eed-ea4128915cd9)





<br>

