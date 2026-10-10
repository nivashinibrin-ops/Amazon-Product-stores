# Amazon Product Store 🛒

## Project Description
Amazon Product Store is a React-based web application that displays a wireless mouse with its price, colour, delivery city, and cart quantity. Users can add items to the cart, remove items, reset the cart, change product colour, update delivery details, and hide or show the product card. The application uses React Hooks such as `useState` and `useEffect` to manage state and dynamically update the browser tab title.

## Features
- Display product details and price.
- Add items to the cart.
- Remove one item from the cart.
- Reset the cart quantity.
- Select product colour.
- Update the delivery city.
- Hide and show the product card.
- Dynamically update the browser tab title.
- Responsive design for desktop and mobile devices.

## Technologies Used
- React.js
- JavaScript
- HTML5
- CSS3
- React Hooks (`useState` and `useEffect`)
- Vite

## Project Structure
```text
my-project/
├── components/
│   ├── header.jsx
│   ├── productcard.jsx
│   └── footer.jsx
├── src/
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
└── README.md
```

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Navigate to the project folder:
   ```bash
   cd my-project
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open the local URL displayed in the terminal to view the application.

## How to Use
1. View the wireless mouse product details.
2. Select a colour from the dropdown menu.
3. Enter or change the delivery city.
4. Click **Add to Cart** to increase the quantity.
5. Click **Remove One** to decrease the quantity.
6. Click **Reset Cart** to clear the cart quantity.
7. Use **Hide Product** and **Show Product** to control product visibility.

## Learning Outcomes
- Understanding React functional components.
- Using props to pass data between components.
- Managing state with the `useState` Hook.
- Understanding side effects and cleanup with the `useEffect` Hook.
- Handling user events in React.
- Applying CSS for responsive web design.

