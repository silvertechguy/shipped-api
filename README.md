# Shipped eCommerce Platform API (Backend)
> eCommerce platform built with the MERN stack & Redux.
![screenshot](https://github.com/silvertechguy/shipped-api/blob/main/shipped.png)
- Check out the deployed site [API - Backend](https://shipped-api.herokuapp.com/)
- If you are looking for the frontend repo, [click here](https://github.com/silvertechguy/shipped)
- Check out the deployed site [Frontend](https://shipped-official.herokuapp.com/)
- API Endpoints: [here](https://github.com/silvertechguy/shipped-api/blob/master/api-spec.md)
## Features
- Full featured shopping cart
- Product reviews and ratings
- Top products carousel
- Product pagination
- Product search feature
- User profile with orders
- Admin product management
- Admin user management
- Admin Order details page
- Mark orders as delivered option
- Checkout process (shipping, payment method, etc)
- PayPal / credit card integration
- Database seeder (products & users)
## Usage
### ES Modules in Node
I'm using ECMAScript Modules in this project. Be sure to have at least Node v14.6+ or you will need to add the "--experimental-modules" flag.
### Env Variables
Create a .env file in then root and add the following
```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
PAYPAL_CLIENT_ID = your paypal client id
```
### Install Dependencies
```
npm install
```
### Run
```
npm run dev
```
### Seed Database
You can use the following commands to seed the database with some sample users and products as well as destroy all data
```
# Import data
npm run data:import
# Destroy data
npm run data:destroy
```
```
Sample User Logins
admin@example.com (Admin)
123456
john@example.com (Customer)
123456
jane@example.com (Customer)
123456
```
### Frontend setup (React.JS)
1. Clone the frontend repo [here](https://github.com/silvertechguy/shipped)
2. Run `npm install`
3. Run `npm start`

👨‍💻 My projects are available at https://silvertechguy.netlify.app
📫 Reach me at my email silvertechguy@gmail.com
twitter https://twitter.com/silvertechyguy
LinkedIn https://linkedin.com/in/silvertechguy

