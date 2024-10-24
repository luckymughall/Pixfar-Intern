# E-Commerce Product Display App

## Project Overview
This is a basic e-commerce app where users can browse products, add them to a cart, and manage the cart. It is built with **React** for the front-end, **Redux Toolkit** for state management, and **Tailwind CSS** for styling. The app offers a smooth user experience, with **React Icons** for visuals and **React Hot Toast** for notifications. Cart data is saved even after refreshing the page using **Redux Persist**.

### Key Features:
- Dockerized for easy setup.
- Browse and view products.
- Add products to the cart.
- Search by category.
- Infinite scrolling for products.
- Cart state persistence.
- Responsive design with Tailwind CSS.
- Notifications via React Hot Toast.

## Steps to Run the App Locally

### Prerequisites:
- **Node.js** (version 14 or higher)
- **npm** or **yarn**

### Steps:
1. Clone the repository:
   ```bash
   https://github.com/luckymughall/Pixfar-Intern.git
   cd your-repo
2. Install dependencies:
npm install
3. Start the development server:
npm run dev
# Key Architectural Decisions
## Redux Toolkit & Redux Persist:
State management is done with Redux Toolkit, which simplifies actions and reducers. Redux Persist ensures cart data stays saved even after a page reload.

## RTK Query:
Used for data fetching, product searching, and infinite scrolling.

## Docker:
The app is containerized with Docker for easier deployment.

## Tailwind CSS:
Tailwind CSS provides responsive and modern styling.

## React Icons & React Hot Toast:
React Icons enhance the look of buttons, and React Hot Toast delivers user-friendly notifications during actions like adding products to the cart.

Tailwind CSS:
Tailwind CSS provides responsive and modern styling.

React Icons & React Hot Toast:
React Icons enhance the look of buttons, and React Hot Toast delivers user-friendly notifications during actions like adding products to the cart.
