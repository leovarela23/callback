# Callback Page

This is a simple callback page that displays query parameters from the URL and highlights them using syntax highlighting for better readability.

## Features
- Displays a header with a title and message indicating a payment has been completed or not.
- Retrieves query string parameters from the URL and displays them in a formatted JSON container.
- Includes syntax highlighting for JSON to make it easier to view parameters.
- Styled using a modern, responsive design for an optimal user experience on both desktop and mobile devices.

## Usage

### 1. Set up the page
Simply place the provided `HTML` code in a `.html` file.

### 2. Pass parameters via the URL
To use the callback page, append query parameters to the URL. For example:

callback.html?paymentStatus=success&amount=100&transactionId=abc123

### 3. View the parameters
The page will parse and display the parameters in a neatly formatted JSON view.
