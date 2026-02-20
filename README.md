# e-plantShopping

A simple plant shopping demo app built with React and Vite.

## Overview

This project is a small single-page application that demonstrates a product listing, a shopping cart, and basic cart management (add/remove items, update quantities, calculate subtotals and totals) using Redux Toolkit.

## Requirements

- Node.js 16+ and npm

## Setup

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

## Key files

- `src/ProductList.jsx` — product listing, navigation, and Add to Cart buttons
- `src/CartItem.jsx` — cart UI: quantity controls, remove, per-item subtotal, total
- `src/CartSlice.jsx` — Redux slice with `addItem`, `removeItem`, and `updateQuantity`

## Notes

- The cart quantity and totals update in real time when the user changes item quantities.
- After adding an item, the corresponding "Add to Cart" button becomes disabled and shows "Added to Cart".
- Checkout workflow is not implemented (placeholder alert).

## Next steps / Improvements

- Add checkout/payment flow
- Persist cart to localStorage or backend
- Add unit and integration tests
