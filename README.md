
# JWT Authentication with Vue.js and Laravel

Welcome to our JWT authentication project built with Vue.js and Laravel! This project provides a seamless user authentication experience, allowing users to securely log in, view their JWT token information, and refresh their token when it expires.

![JWT Authentication Demo](demo.gif)

## Features

- **Secure Authentication**: Safely authenticate users using JWT (JSON Web Tokens) for secure communication between the frontend and backend.
- **Token Info Display**: Display the current JWT token along with its expiration time for user reference.
- **Automatic Token Refresh**: The app automatically refreshes the token when it's about to expire. When the token expires, a refresh button appears. Clicking it triggers a request to the backend for a new token, ensuring uninterrupted user session.
  
## Technologies Used

- **Vue.js**: A progressive JavaScript framework for building user interfaces.
- **Tailwind CSS**: A utility-first CSS framework for quickly building custom designs.
- **Laravel**: A PHP web application framework for building efficient and secure web applications.
- **JWT (JSON Web Tokens)**: A compact, URL-safe means of representing claims to be transferred between two parties.
- **Axios**: A promise-based HTTP client for making requests to the backend API.

## Getting Started

Follow these instructions to get the project up and running on your local machine:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/username/JWT
   cd JWT
   ```

2. **Install Dependencies**:

   ```bash
   npm install
   ```

3. **Run the Development Server**:

   ```bash
   npm run serve
   ```

4. **Open the Application**:

   Visit `http://localhost:8080` in your browser to view the application.

## Backend Integration

For full functionality, make sure to integrate this frontend project with a Laravel backend that handles user authentication and token management. You can find a sample Laravel backend implementation for JWT authentication in the [laravel-jwt-auth](https://github.com/yourusername/laravel-jwt-auth) repository.

## Usage

1. **Login**: Enter your credentials in the login form and submit. Upon successful authentication, you will be redirected to the Token Info page.

2. **Token Info**: View your current JWT token and its expiration time. The timer will track the token's expiration, and if expired, a refresh button will appear.

3. **Token Refresh**: Click the refresh button to request a new token from the backend. The token will be automatically updated without requiring a page reload.

## Contributing

Contributions are welcome! Feel free to submit bug reports, feature requests, or pull requests to help improve the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions, suggestions, or just want to say hi, feel free to reach out to us:

- **Email**: imranhossain16.ctg@gmail.com
- **GitHub**: [imranctg16](https://github.com/imranctg16)

---
Happy coding! 🚀
