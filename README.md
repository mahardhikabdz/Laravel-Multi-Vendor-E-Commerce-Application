# Laravel Multi-Vendor E-Commerce Application 🛒

![Laravel Multi-Vendor E-Commerce Application](https://img.shields.io/badge/Version-1.0.0-brightgreen.svg) ![License](https://img.shields.io/badge/License-MIT-blue.svg) ![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen.svg)

Welcome to the **Laravel Multi-Vendor E-Commerce Application** repository! This project is designed to provide a comprehensive platform for multi-vendor e-commerce. With a rich set of features and modules, it allows multiple vendors to sell their products seamlessly. The application includes a dedicated API with Passport authentication, ensuring secure access and integration.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Features ✨

- **Multi-Vendor Support**: Allow multiple vendors to register and sell their products.
- **User Authentication**: Secure login and registration for users and vendors using Laravel Passport.
- **Payment Integration**: Support for PayPal and other payment gateways.
- **Shipping Management**: Calculate shipping charges based on location and weight.
- **Product Management**: Vendors can add, edit, and delete their products easily.
- **Order Management**: Users can view and manage their orders.
- **Webhook Integration**: Set up webhooks for real-time notifications and updates.
- **DataTables Integration**: Efficient data handling for large datasets.
- **API Integration**: Extensive API for third-party integrations.

## Technologies Used 🛠️

- **Laravel**: The core framework for building the application.
- **MySQL**: Database management system for storing data.
- **Passport**: For API authentication.
- **JavaScript**: For dynamic content and interactions.
- **HTML/CSS**: For the front-end layout and styling.
- **Bootstrap**: For responsive design.
- **jQuery**: For simplifying JavaScript operations.

## Installation ⚙️

To set up the application locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/mahardhikabdz/Laravel-Multi-Vendor-E-Commerce-Application.git
   cd Laravel-Multi-Vendor-E-Commerce-Application
   ```

2. **Install Dependencies**:
   Use Composer to install the required PHP packages.
   ```bash
   composer install
   ```

3. **Set Up Environment File**:
   Copy the `.env.example` file to `.env` and configure your database and other settings.
   ```bash
   cp .env.example .env
   ```

4. **Generate Application Key**:
   Run the following command to generate the application key.
   ```bash
   php artisan key:generate
   ```

5. **Run Migrations**:
   Create the necessary database tables by running the migrations.
   ```bash
   php artisan migrate
   ```

6. **Install NPM Packages**:
   If you need to compile front-end assets, run:
   ```bash
   npm install
   npm run dev
   ```

7. **Start the Development Server**:
   Launch the application locally.
   ```bash
   php artisan serve
   ```

Now, you can access the application at `http://localhost:8000`.

## Usage 📖

Once the application is up and running, you can:

- **Register as a User or Vendor**: Navigate to the registration page and fill out the form.
- **Login**: Use your credentials to access the dashboard.
- **Manage Products**: Vendors can add, update, or remove their products.
- **Place Orders**: Users can browse products and place orders directly.
- **Check Order Status**: Users can view their order history and status.

## API Documentation 📚

The application provides a robust API for third-party integrations. You can find the API documentation in the `docs/api.md` file. Here are some key endpoints:

- **Authentication**:
  - `POST /api/login`: User login.
  - `POST /api/register`: User registration.

- **Products**:
  - `GET /api/products`: List all products.
  - `POST /api/products`: Create a new product.

- **Orders**:
  - `GET /api/orders`: List all orders.
  - `POST /api/orders`: Create a new order.

For detailed API usage, refer to the documentation linked above.

## Contributing 🤝

We welcome contributions to improve the application. If you would like to contribute, please follow these steps:

1. **Fork the Repository**: Click the "Fork" button at the top right of this page.
2. **Create a New Branch**: 
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Make Your Changes**: Implement your feature or fix.
4. **Commit Your Changes**:
   ```bash
   git commit -m "Add some feature"
   ```
5. **Push to the Branch**:
   ```bash
   git push origin feature/YourFeatureName
   ```
6. **Open a Pull Request**: Go to the original repository and create a pull request.

## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Links 🔗

For the latest updates and releases, visit our [Releases](https://github.com/mahardhikabdz/Laravel-Multi-Vendor-E-Commerce-Application/releases) section. Download and execute the files to get started with the latest version.

Feel free to explore the application, and don't hesitate to check the [Releases](https://github.com/mahardhikabdz/Laravel-Multi-Vendor-E-Commerce-Application/releases) section for updates and new features. 

## Conclusion

Thank you for checking out the Laravel Multi-Vendor E-Commerce Application! We hope this project serves your needs well. If you have any questions or suggestions, feel free to reach out or contribute. Happy coding!