# Razorpay Test Project

Welcome to the **Razorpay Test Project**! This project demonstrates the integration of Razorpay payment gateway with a Laravel application.

## Overview

This repository provides a simple example of how to set up and use Razorpay for processing payments in a Laravel environment. It covers the basics of configuration, payment initiation, and handling payment responses.

## Features

- Seamless Razorpay integration
- Secure payment processing
- Example payment form
- Laravel best practices

## Getting Started

### Prerequisites

- PHP >= 8.0
- Composer
- Laravel >= 9.x
- Razorpay account

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Razorpay_test.git
    cd Razorpay_test
    ```

2. Install dependencies:
    ```bash
    composer install
    ```

3. Copy `.env.example` to `.env` and update your environment variables, especially Razorpay keys.

4. Generate application key:
    ```bash
    php artisan key:generate
    ```

5. Run migrations:
    ```bash
    php artisan migrate
    ```

### Configuration

Add your Razorpay API keys to the `.env` file:
```
RAZORPAY_KEY=your_key
RAZORPAY_SECRET=your_secret
```

## Usage

- Start the Laravel development server:
  ```bash
  php artisan serve
  ```
- Visit `http://localhost:8000` and follow the instructions to test payments.

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

This project is open-source and available under the [MIT License](LICENSE).

---

Happy coding!
