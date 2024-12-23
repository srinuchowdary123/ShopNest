# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
#   B e s t - b u y 
 
 Here is a more concise breakdown of the functionality in your code:

1. **Firebase Setup**: 
   - You’ve initialized Firebase with the necessary configuration and set up authentication (`auth`) and Firestore (`db`).

2. **Cart Data Functions**:
   - `fetchCartData`: Fetches the user's cart data from Firestore.
   - `updateCartData`: Updates the cart data in Firestore.

3. **Authentication Functions**:
   - `signup`: Creates a new user with email, password, and display name.
   - `signin`: Signs in a user using email and password.

4. **Cart Management** (React Components):
   - `CartDetails`: Displays cart items, handles adding/removing items, calculates the total, and manages the UI for logged-in users.
   - `CartPreview`: Displays a cart preview button with the number of items, and when clicked, shows the cart details in a popover.

5. **Cart State and Display**:
   - Uses Redux to manage the cart state (`addtocart`, `removeCart` actions).
   - `getUniqueCartItems`: Ensures cart items are unique, and their count is updated.
   - The cart summary (subtotal, shipping, tax, total) is calculated and displayed.

**Key Points**:
- You’re integrating Firebase for authentication and Firestore for storing user cart data.
- Your UI components manage cart items and display totals dynamically.
