# Pizzas Restaurants API
This is a pizzas restaurants Rails backend API built using the Rails framework.

## Project Description 
This project API is purposely for tracking pizzas restaurants.It has the following resources:
- Restaurants
- Pizzas
- Restaurant_pizzas(this is the joint table for pizzas and restaurants)

## Database Relationships
This Rails API utilizes a many-to-many relationships approach. A restaurant has many pizzas and a pizza has many restaurants. The RestaurantPizza belongs to both Restaurant and Pizza therefore acts as the joint table for the two models.

## Requirements
- Access to a computer,tablet or phone.
- An access to internet.


## Deployment
To access the API click on the deployed link: "https://pizzas-code-challenge-backend.onrender.com/restaurants"

## Installation
To use this API, you must have installed:
- ruby -v 2.7.4
- rails -v 7.0.4.3
- Postgress installed on your computer/laptop.

### Follow the steps below to install the Api:
- Clone the repository

   git clone : "https://github.com/nthokiesther09/Pizzas-Code-Challenge"

- bundle install to install dependencies
- Set up the database:
   rails db:migrate
   rails db:seed
- Start the server:
   rails s
Once the server is up and runnning, you should be able to access the API at `https://localhost:3000`.

With the server running, you can use your preferred API platform such as `Postman` or `Thunder client` to try out the CRUD operations (GET, POST, and DELETE) using the provided `faker` data. Specifically, the API provides for the following CRUD operations
1. GET /restaurants 
2. GET /restaurants/:id
3. DELETE /restaurants/:id
4. GET /pizzas
5. POST /restaurant_pizzas

## Technologies Used
- Ruby
- Rails
- SQL
- Git

## Authors
Esther Musyoka [nthokiesther09]-("https://github.com/nthokiesther09/Pizzas-Code-Challenge")

## LICENSE
This project is under ISC License









