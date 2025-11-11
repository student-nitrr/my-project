# React E-Commerce Platform# E-Commerce Website



A fully responsive e-commerce website built with React.js, featuring product browsing, shopping cart functionality, and user authentication pages.A Ecommerce Website made with React.js Framework.



## 🌐 Live Demo

## Demo

**Vercel Deployment:** [my-project-student-nitrrs-projects.vercel.app](https://my-project-student-nitrrs-projects.vercel.app/)

https://reactjs-ecommerce-app.vercel.app/

## ✨ Features

## Features

- 🛍️ **Product Catalog** - Browse products with filtering by category

- 🛒 **Shopping Cart** - Add/remove items from cart with persistent state- Easy to integrate with Backend

- 🔍 **Product Search & Filtering** - Filter by category (Men's, Women's, Jewelry, Electronics)- Fully Responsive

- 📱 **Fully Responsive Design** - Works perfectly on desktop, tablet, and mobile devices

- 🎨 **Modern UI** - Built with Bootstrap 5 for clean and professional design

- ⚡ **Fast Performance** - Optimized for production with code splitting## Screenshots

- 🔐 **Authentication Pages** - Login and Registration pages (UI ready for backend integration)

- 🛒 **Checkout Page** - Complete checkout flow for orders![App Screenshot](https://i.ibb.co/fQ293tm/image.png)

- 📄 **Static Pages** - About and Contact pages included



## 🚀 Quick Start

## Run Locally

### Prerequisites

- Node.js (v14 or higher)Clone the project

- npm or yarn

```bash

### Installation  git clone https://github.com/ssahibsingh/React_E-Commerce

```

1. **Clone the repository**

   ```bashGo to the project directory

   git clone https://github.com/student-nitrr/my-project.git

   cd my-project```bash

   ```  cd React_E-Commerce

```

2. **Install dependencies**

   ```bashInstall dependencies

   npm install

   ``````bash

  npm install

3. **Start the development server**```

   ```bash

   npm startStart the server

   ```

   The app will open at `http://localhost:3000````bash

  npm start

4. **Build for production**```

   ```bash

   npm run build

   ```

## Tech Stack

## 📁 Project Structure

* [React](https://reactjs.org/)

```* [Redux](https://redux.js.org/)

src/* [Bootstrap](https://getbootstrap.com/)

├── components/* [Fake Store API](https://fakestoreapi.com/)

│   ├── Navbar.jsx          # Navigation component

│   ├── Footer.jsx          # Footer component## Contributing

│   ├── Products.jsx        # Product list with filtering

│   ├── ScrollToTop.jsx     # Scroll to top utilityContributions are always welcome!

│   └── index.js            # Component exportsJust raise an issue, we will discuss it.

├── pages/

│   ├── Home.jsx            # Home page

│   ├── Products.jsx        # Products page## Feedback

│   ├── Product.jsx         # Product detail page

│   ├── Cart.jsx            # Shopping cart pageIf you have any feedback, please reach out to me [here](https://ssahibsingh.github.io/#contact)

│   ├── Checkout.jsx        # Checkout page

│   ├── Login.jsx           # Login page

│   ├── Register.jsx        # Registration page
│   ├── AboutPage.jsx       # About page
│   ├── ContactPage.jsx     # Contact page
│   └── PageNotFound.jsx    # 404 page
├── redux/
│   ├── store.js            # Redux store configuration
│   ├── action/
│   │   └── index.js        # Redux actions
│   └── reducer/
│       ├── handleCart.js   # Cart reducer
│       └── index.js        # Root reducer
├── index.js                # App entry point
└── index.css               # Global styles
```

## 🛠️ Tech Stack

### Frontend
- **React 18** - UI library
- **Redux & Redux Toolkit** - State management
- **React Router v6** - Client-side routing
- **Bootstrap 5** - CSS framework
- **React Hot Toast** - Notifications
- **React Loading Skeleton** - Skeleton loading states
- **React Fast Marquee** - Marquee component

### API
- **Fake Store API** - Public API for product data (https://fakestoreapi.com/)

### Deployment
- **Vercel** - Hosting platform

## 🎯 Available Scripts

- `npm start` - Run development server
- `npm run build` - Create production build
- `npm test` - Run test suite
- `npm run eject` - Eject from Create React App (irreversible)

## 🔧 Key Components

### Redux Store
- **Actions**: Add to cart, remove from cart, clear cart
- **State**: Shopping cart items and total price
- **Reducers**: Cart management logic

### Pages
1. **Home** - Landing page with featured products
2. **Products** - Full product catalog with category filtering
3. **Product Details** - Individual product page with related products
4. **Cart** - Shopping cart with item management
5. **Checkout** - Order summary and payment flow
6. **Authentication** - Login and Registration forms
7. **About** - Company information
8. **Contact** - Contact information and form
9. **404** - Page not found error page

## 📝 Configuration

The app uses environment variables for configuration. Create a `.env` file in the root directory:

```env
REACT_APP_API_URL=https://fakestoreapi.com
CI=false
```

## 🚀 Deployment on Vercel

This project is already configured for Vercel deployment:

1. Connect your GitHub repository to Vercel
2. Vercel will automatically detect the React app
3. Click "Deploy"
4. Your app will be live in minutes!

### Vercel Configuration
- Build command: `npm run build`
- Output directory: `build`
- Install command: `npm install`

## 🐛 Troubleshooting

### Build Issues
If you encounter build errors:
1. Clear node_modules: `rm -rf node_modules package-lock.json`
2. Reinstall dependencies: `npm install`
3. Clear npm cache: `npm cache clean --force`

### Port Already in Use
If port 3000 is already in use:
```bash
npm start -- --port 3001
```

## 🔄 Backend Integration

To integrate with a custom backend:

1. Create a `.env` file with your API URL:
   ```env
   REACT_APP_API_URL=https://your-backend-api.com
   ```

2. Update API calls in components to use the environment variable:
   ```javascript
   const API_URL = process.env.REACT_APP_API_URL;
   const response = await fetch(`${API_URL}/products`);
   ```

## 📄 License

This project is open source and available under the MIT License.

## 👨‍💻 Author

**Saksham Singh**
- GitHub: [@student-nitrr](https://github.com/student-nitrr)

## 🤝 Contributing

Contributions are always welcome! 

To contribute:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Support

For support, email or create an issue on GitHub.

## 🔗 Useful Links

- [React Documentation](https://react.dev/)
- [Redux Documentation](https://redux.js.org/)
- [Bootstrap Documentation](https://getbootstrap.com/docs/)
- [Fake Store API Docs](https://fakestoreapi.com/)
- [Vercel Documentation](https://vercel.com/docs)
