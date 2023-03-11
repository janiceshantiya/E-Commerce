Software Requirement Specification  (E-Commerce)

Purpose:
   This project aims to create an E-commerce website to provide a satisfying consumer and seller 
experience. The SRS aims to cover the entire scope of the project. In this modern fast-paced and 
busy world, E-commerce platforms provide a very convenient way for people across the world to 
get their desired products at their doorstep. Hence, E-commerce platforms must be fast, 
convenient and efficient to cater to the needs of both the buyer and seller.

Product Scope:
   This software is an e-commerce platform which helps customers to make effective purchases and 
helps sellers in increasing the sales and management of their products. Each customer and seller 
has access to pages where they can organize and see all their records. There are options to 
optimize search and keep track of the products one likes. There is a portal for customer support 
too in case of any discrepancies.

Overall Description:
Product Perspective:
   Our E-commerce system is a stand-alone system which aims to incorporate all major features 
which a customer would expect while ordering goods from their phone or personal computer.
Product Functions
The E-commerce Platform will have 3 different modules namely,
   1.seller module
   2.buyer module
   3.logistics module
Our project has the following features:
   • A homepage for the customer where he/she can view new products and discounts.
   • The seller's homepage where he/she can view their current and past shipments.
   • Mark products as favorites or put them in the cart and order them.
   • Tracking of the delivery status. A customer may post reviews of a product.
   • Customers receive notifications regarding sales and discounts.
   • Portal for customer support in case of any discrepancies.
   • Return and replacement options for products. 
   
Operating Environment:
   The product will be available as a web application. Since the product is a web-app it is 
available on all operating systems and platforms. Majorly, the website will run on web 
browsers like Google Chrome, Microsoft Edge, Safari, Mozilla Firefox. Also, as a future 
enhancement an application could be developed for android which will make our product 
available to mobile users.

Functional Requirements:
    REQ-1: User must be logged in. 
    REQ-2: The product must be available.
    REQ-3: Seller must allow the product to be shipped to the user's location.
    REQ-4: Shipment facility should be able to update the product’s current location.
    REQ-5: Buyer should be able to track the shipment.
    
Nonfunctional Requirements:
1.Performance Requirements
   The website/app must be fast, interactive and must provide a quick response. In the case of 
opening applications, forms and saving the settings or sessions there must not be a delay of more 
than 1-5 seconds. On connection to databases, sorting categories and ordering of products there 
should be no delays and the operation must be performed in less than 1-5 seconds for opening, 
sorting, computing, etc.
2. Safety Requirements
   Only authorized buyers/sellers should be able to query and change the contents of the database. 
The website users should be authenticated before they can use the feature exclusively for them. 
The usernames and passwords of users should be encrypted and protected from unauthorized 
access. Data security should be maintained.
3.Security Requirements
   • HTTPS protocols are used for communication due to their secure nature.
   • User login is secured by JWT authentication with role-based authorization.
   • Cross Origin access is restricted at service level.
   
Hardware Interfaces:
   Since the website will be hosted on external servers, there won’t be any hardware 
requirements as such on our part. The user on the other hand would need either a smartphone 
or a desktop/laptop to access the website.

Software Interfaces:
   Our product consists of a database, frontend and backend. There will be a connection 
between frontend and backend for passing information back and forth. The backend will be 
connected to the database for accessing information and storing transactions, product orders. The 
customer if using a smartphone must have Android version 4.4 or above and if using a desktop, 
he/she must have Windows 7 or above/ Ubuntu /iOS Operating System.

User Interfaces:
   We plan to create a web application. Since we plan to sell products belonging to different 
categories, we will create an easy-to-use interface which would have a search bar to search for 
products based on the category, price, ratings as well as product specifications. We will have two 
dashboards, one for the sellers and one for the customer. On this dashboard, the customer will be 
able to view various deals and discounts as well as top products for each category, the seller can 
see all the products sold, uploaded for sale by him. Logistics will have a separate login to track 
all the shipments. Each product will have its own page which will list its price, reviews, images 
and link to order the product. For a particular user, they will have a cart which will allow them to 
add or remove products. The website is mobile responsive, hence, can be accessed on phones and 
tablets. For the sellers, they will be able to view their current and past shipment on a dashboard
