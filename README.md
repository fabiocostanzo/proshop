# Proshop

Complete eCommerce web app sample using MERN stack. \
The production build is hosted on [render](render.com) and you can find it [HERE](https://proshop-a2fe.onrender.com/)\
(Free plan, could take up to 30 seconds if website is inactive for long)

## Features

- Register a new user
- Login / Logout (auth with Json Web Token)
- Add to cart (cart handled with local storage)
- Complete checkout process
- Payment using PayPal or Credit card (sandbox)
- Write product customer reviews
- Admin functionalities:
  - List all products / orders / users
  - Create a new product (sample)
  - Edit a product / user
  - Set order as delivered

## Available Scripts

In the project directory, you can run:

### `npm run dev`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm run data:import`

Populate MongoDB Product collection with sample data (sample data here -> products.js)

### `npm run data:destroy`

Clean all Collections in MongoDB, to get a fresh new environment

### `npm run build`

Install all dependencies and builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!
