# QR Code Generator

This project is a simple Node.js application that generates a QR code from a user-provided URL. The application uses the `inquirer` package to prompt the user for input, the `qr-image` package to generate the QR code, and the `fs` module to save the QR code image and the URL to a file.

---

## Features

- **Interactive Input**: Prompts the user to input a URL using `inquirer`.
- **QR Code Generation**: Converts the URL into a QR code image using `qr-image`.
- **File Saving**: Saves the QR code as a PNG image and the URL as a text file.

---

## How to Use

1. Clone this repository or copy the code into a local directory.
2. Ensure you have [Node.js](https://nodejs.org/) installed on your system.
3. Install the required dependencies by running:
   ```bash
   npm install inquirer qr-image

---

## Acknowledgements

This project was inspired by a tutorial in **[The Complete 2024 Web Development Bootcamp](https://www.udemy.com/course/the-complete-web-development-bootcamp/)** on Udemy. I would like to express my gratitude to the author **Angela Yu** for providing the foundational knowledge that made this project possible.
