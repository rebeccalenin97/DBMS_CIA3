DBMS CIA 3
TEAM:
Florentina Francis 2462070
Sandra Shaju 2462143
Rebecca Lenin Koshy 2462134
# Cuddlecot - Kids Clothing E-Commerce Platform

A professional full-stack e-commerce application for kids' clothing built with Angular, Node.js, Express, and MySQL.

## Quick Start

### Prerequisites
- Node.js v18+
- MySQL 8.0+
- Angular CLI v18+

### Installation

**1. Backend Setup**
```bash
cd backend
npm install express mysql2 cors
mysql -u root -p < database.sql  # Password: root@123
npm start
```

**2. Frontend Setup**
```bash
ng add @angular/material
ng serve
```

**3. Access Application**
- URL: http://localhost:4200
- Login: rahul@example.com / password123

##  Features

### Frontend
Angular Material UI with modern purple gradient theme
Responsive design for all devices
Real-time cart updates with live badge count
Product filtering (category, age, price)
Loading spinners and snackbar notifications
Professional hover effects and animations
User authentication with session management

### Backend
RESTful API with 10 endpoints
MySQL database with relational schema
User authentication
Shopping cart management
Order processing and history
CORS enabled for Angular integration

### Database
5 tables (users, products, cart, orders, order_items)
15 sample products (kids clothing)
5 test user accounts
Foreign key relationships

## Technology Stack

**Frontend:**
- Angular 18
- Angular Material
- TypeScript
- RxJS
- CSS3

**Backend:**
- Node.js
- Express.js
- MySQL2
- CORS

**Database:**
- MySQL 8.0

## Documentation

- [SETUP_GUIDE.md](SETUP_GUIDE.md) - Complete setup instructions
- [QUICK_START.md](QUICK_START.md) - Quick reference guide
- [ARCHITECTURE.txt](ARCHITECTURE.txt) - System architecture diagram
- [TRANSFORMATION_SUMMARY.md](TRANSFORMATION_SUMMARY.md) - Project evolution

## API Endpoints

- `GET /api/products` - Get all products
- `POST /api/login` - User authentication
- `GET /api/cart/:userId` - Get user's cart
- `POST /api/cart` - Add to cart
- `POST /api/orders` - Create order
- And more...

## Test Credentials

```
Email: rahul@example.com
Password: password123
```

## Screenshots

Professional UI with:
- Modern purple gradient color scheme
- Material Design components
- Responsive grid layouts
- Smooth animations

## Troubleshooting

See [SETUP_GUIDE.md](SETUP_GUIDE.md) for detailed troubleshooting steps.

## License

This project was built for educational purposes.

---

**Built with ❤️ for kids' fashion**
- Checkout flow
- Backend / API integration



## Tech Stack
- Angular
- TypeScript
- HTML & CSS




