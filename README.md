This project is a web application built using the Express framework for the backend, MongoDB for the database, and various middlewares to enhance functionality and security. The application includes routes for user authentication, user management, and handling listings. It also serves static files and includes error handling mechanisms.

## Backend Technologies Used

- **Express**: A fast, unopinionated, minimalist web framework for Node.js.
- **Mongoose**: An Object Data Modeling (ODM) library for MongoDB and Node.js.
- **dotenv**: A module that loads environment variables from a .env file into process.env.
- **cookie-parser**: Middleware to parse cookies attached to client requests.
- **path**: A Node.js module to work with file and directory path

  This project is a React application utilizing `react-router-dom` for client-side routing. It includes several pages such as Home, Sign In, Sign Up, About, Profile, Create Listing, Update Listing, Listing, and Search. The application features both public and private routes, with protected routes only accessible to authenticated users.

## Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **React Router**: A library for routing in React applications.
- **Component-Based Architecture**: The application is divided into reusable components.
- **BrowserRouter**: Wraps the entire application to enable client-side routing.
- **Header**: A common header component displayed on all pages.
- **Routes**: Defines the various routes of the application.

## Features

1. **Property Listings**:
   - Users can create new property listings with details such as name, address, description, price, bedrooms, bathrooms, and images.
   - Listings can be updated or deleted by the authenticated user who created them.

2. **Property Viewing**:
   - Users can browse through available property listings.
   - Each listing displays key details including images, location, description, price, and specifications (bedrooms, bathrooms).

3. **Search Functionality**:
   - Users can search for properties based on location, price range, number of bedrooms, etc.
   - Search results are displayed dynamically, updating as users input search criteria.
