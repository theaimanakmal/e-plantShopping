# Paradise Nursery – e-plantShopping

**Project name:** Paradise Nursery (e-plantShopping)

Paradise Nursery is an online plant shop built with **React**, **Redux Toolkit** and **Vite**.
Customers can browse houseplants by category, add them to a shopping cart, change quantities,
and see the total cost of their order.

## Features

- **Landing page** with a background image, the company name and a **Get Started** button
- **About Us** section describing the company
- **Product listing page** with 18 houseplants in 3 categories (Air Purifying, Aromatic, Insect Repellent),
  each showing a thumbnail, name, description and price
- **Add to Cart** buttons that add the plant, disable themselves once added, and update the cart icon count
- **Navbar** on the product and cart pages with links to Home, Plants and Cart
- **Shopping cart page** showing each plant's thumbnail, name, unit price, subtotal, quantity
  controls (+ / −), a Delete button, the total cart amount, a Checkout button ("Coming Soon")
  and a Continue Shopping button

## Tech used

- React 18
- Redux Toolkit and React Redux (cart state in `CartSlice.jsx`)
- Vite

## How to run

```bash
npm install
npm run dev
```

Then open the link shown in the terminal (usually http://localhost:5173).
