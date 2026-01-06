# 🛒 TechStore - E-Commerce Website

![Project Banner](https://via.placeholder.com/1200x400/6366F1/ffffff?text=TechStore+E-Commerce)

> A fully functional e-commerce website with shopping cart, product filtering, and checkout functionality built with pure HTML, CSS, and JavaScript.

[![Live Demo](https://img.shields.io/badge/Live-Demo-success?style=for-the-badge)](https://kusaselihle07.github.io/ecommerce-website/)
[![GitHub](https://img.shields.io/badge/GitHub-Repo-blue?style=for-the-badge&logo=github)](https://github.com/kusaselihle07/ecommerce-website)

---

## 📸 Screenshots

### Desktop View
![Desktop Screenshot](https://via.placeholder.com/800x500/F3F4F6/6366F1?text=Add+Desktop+Screenshot)

### Mobile View
<img src="https://via.placeholder.com/300x600/F3F4F6/6366F1?text=Add+Mobile+Screenshot" width="300">

---

## 🎯 About The Project

TechStore is a modern, fully functional e-commerce website that I built to demonstrate my front-end development skills. It features a complete shopping experience including product browsing, category filtering, shopping cart management, and checkout functionality.

This project showcases my ability to:
- Build interactive user interfaces
- Manage application state with JavaScript
- Create responsive designs that work on all devices
- Implement complex user flows and interactions

### ✨ Key Features

- ✅ **12 Real Products** - Laptops, phones, and accessories with realistic pricing
- ✅ **Category Filtering** - Filter products by laptops, phones, or accessories
- ✅ **Shopping Cart** - Add, remove, and update product quantities
- ✅ **Live Total Calculator** - Real-time price calculations
- ✅ **Quantity Controls** - Increase or decrease item quantities in cart
- ✅ **Checkout System** - Complete purchase flow with order confirmation
- ✅ **Success Notifications** - Visual feedback when items are added to cart
- ✅ **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- ✅ **Modern UI/UX** - Clean, professional design with smooth animations
- ✅ **No Dependencies** - Built with pure vanilla JavaScript (no frameworks!)

---

## 🛠️ Built With

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with CSS Grid, Flexbox, and animations
- **JavaScript (ES6+)** - Shopping cart logic, state management, DOM manipulation
- **CSS Variables** - Consistent theming and easy customization

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic text editor (optional, for modifications)

### Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/kusaselihle07/ecommerce-website.git
   cd ecommerce-website
   ```

2. **Open the project**
   - Simply open `index.html` in your web browser
   - Or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

3. **View in browser**
   - Navigate to `http://localhost:8000`
   - Or just double-click `index.html`

---

## 💡 How It Works

### Shopping Cart Logic

The shopping cart uses JavaScript arrays and objects to manage state:

```javascript
// Cart stores products with quantities
let cart = [
  { id: 1, name: "MacBook Pro", price: 2499, quantity: 2 },
  { id: 2, name: "iPhone 15 Pro", price: 999, quantity: 1 }
];

// Total is calculated dynamically
const total = cart.reduce((sum, item) => sum + (item.price * item.quantity), 0);
```

### Key Functions

- `addToCart()` - Adds products or increases quantity
- `updateQuantity()` - Modifies item quantities
- `removeFromCart()` - Removes items from cart
- `filterProducts()` - Filters products by category
- `checkout()` - Processes the order

---

## 🎓 What I Learned

Building this project helped me strengthen several important skills:

### JavaScript Skills
- **State Management**: Managing complex application state without a framework
- **Array Methods**: Using map(), filter(), reduce(), and find() effectively
- **Event Handling**: Managing click events, modals, and user interactions
- **DOM Manipulation**: Dynamically updating the UI based on data changes
- **ES6+ Features**: Arrow functions, template literals, spread operator, destructuring

### CSS Skills
- **CSS Grid & Flexbox**: Creating responsive layouts
- **CSS Variables**: Maintaining consistent theming
- **Animations**: Adding smooth transitions and hover effects
- **Responsive Design**: Mobile-first approach with media queries

### Challenges Overcome

1. **Challenge**: Managing cart state across different functions
   - **Solution**: Created centralized `updateCart()` function that syncs all UI elements

2. **Challenge**: Calculating totals with multiple quantities
   - **Solution**: Used JavaScript's `reduce()` method for elegant calculations

3. **Challenge**: Making the modal accessible and user-friendly
   - **Solution**: Added click-outside-to-close and proper z-index management

---

## 🔮 Future Improvements

- [ ] Add product search functionality
- [ ] Implement user authentication
- [ ] Add product reviews and ratings
- [ ] Integrate with a real payment gateway (Stripe/PayPal)
- [ ] Add wish list functionality
- [ ] Implement backend with Node.js and MongoDB
- [ ] Add product image uploads
- [ ] Create admin panel for product management
- [ ] Add email notifications for orders
- [ ] Implement dark mode toggle

---

## 📱 Responsive Design

This website is fully responsive and tested on:
- **Desktop**: 1920px and above
- **Laptop**: 1024px - 1919px
- **Tablet**: 768px - 1023px
- **Mobile**: 320px - 767px

---

## 🎨 Color Palette

| Color | Hex Code | Usage |
|-------|----------|-------|
| Primary Purple | `#6366F1` | Buttons, accents, branding |
| Secondary Purple | `#8B5CF6` | Gradients, hover states |
| Success Green | `#10B981` | Checkout button, success messages |
| Danger Red | `#EF4444` | Remove buttons, cart count |
| Dark Gray | `#1F2937` | Text, headings |
| Light Gray | `#F3F4F6` | Backgrounds, sections |

---

## 📂 Project Structure

```
ecommerce-website/
│
├── index.html          # Main HTML file (contains all code)
└── README.md           # Project documentation
```

*Note: This is a single-file project for simplicity. In a production environment, CSS and JavaScript would be separated into individual files.*

---

## 🤝 Contributing

This is a personal portfolio project, but suggestions and feedback are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add some improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Kusaselihle Kusasa**

- GitHub: [@kusaselihle07](https://github.com/kusaselihle07)
- Email: sizolihle07@gmail.com
- Portfolio: [Coming Soon]

---

## 🙏 Acknowledgments

- Product icons: Emoji characters for visual representation
- Inspiration: Modern e-commerce websites like Amazon, Shopify
- Learning resources: SheCodes, PLP Academy
- Color palette: Modern gradient design trends

---

## 📊 Project Stats

![GitHub repo size](https://img.shields.io/github/repo-size/kusaselihle07/ecommerce-website)
![GitHub last commit](https://img.shields.io/github/last-commit/kusaselihle07/ecommerce-website)
![GitHub language count](https://img.shields.io/github/languages/count/kusaselihle07/ecommerce-website)

---

## 💬 Feedback

If you have any feedback or suggestions, feel free to reach out or open an issue on GitHub!

---

⭐️ **If you found this project helpful or interesting, please consider giving it a star!**

**Built with 💜 by Kusaselihle Kusasa**

[⬆ Back to Top](#-techstore---e-commerce-website)
