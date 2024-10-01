
# E-commerce API with Django, Redis Caching, and Real-Time Notifications

## Introduction
This project is a fully functional REST API for a small e-commerce system that allows users to register, browse products, and place orders. It includes real-time order status updates using Django Channels, caching with Redis, and token-based authentication using JWT.

## Features:
- **User Authentication** (JWT-based)
- **Product Management** with categories and stock tracking
- **Order System** with real-time updates
- **Caching** with Redis for performance optimization
- **Pagination & Filtering** for large datasets
- **Real-Time Notifications** via Django Channels

## Setup Instructions

### 1. Clone the Repository:
```bash
git clone <your-repo-url>
cd ecommerce
```

### 2. Install Dependencies:
Use the `requirements.txt` to install the required dependencies:
```bash
pip install -r requirements.txt
```

### 3. Database Setup:
Ensure PostgreSQL is installed and configure the `DATABASES` setting in `settings.py`.

```bash
python manage.py migrate
```

### 4. Redis Setup:
Ensure Redis is installed and running for caching.

### 5. Run the Development Server:
Start the server using the following command:
```bash
python manage.py runserver
```

### 6. Run Django Channels:
Ensure Django Channels is configured properly for WebSocket-based real-time notifications.

## Usage
- Register and login to obtain your JWT token.
- Browse and filter products.
- Add products to your cart and place orders.
- Receive real-time notifications when your order status changes.

