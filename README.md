# QR Code Generator

A lightweight, client-side QR code generator web application built with vanilla JavaScript. Generate QR codes instantly from any text or URL with a clean, responsive interface.

## 🚀 Live Demo

[**Try it here →**](https://tolik4813.github.io/qrCode__generator/)

## ✨ Features

- **Instant QR Code Generation** - Create QR codes from text or URLs in real-time
- **Input Validation** - Visual feedback for empty inputs with smooth error animations
- **Responsive Design** - Works seamlessly on desktop and mobile devices
- **Zero Dependencies** - Built with pure HTML, CSS, and JavaScript
- **Clean UI/UX** - Modern, minimalist interface with smooth transitions
- **Client-Side Processing** - No backend required, all processing happens in the browser

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom styling with animations and transitions
- **Vanilla JavaScript** - Pure JavaScript, no frameworks
- **QR Server API** - External API for QR code generation
- **GitHub Pages** - Hosting and deployment

## 📋 Usage

1. Enter your text or URL in the input field
2. Click the "Generate QR Code" button
3. Your QR code will appear below the input field
4. Scan the QR code with any QR code reader app

## 📁 Project Structure

```
qrCode__generator/
├── index.html      # Main HTML structure
├── style.css       # Styles and animations
├── script.js       # QR code generation logic
└── README.md       # Project documentation
```

## 🎨 Screenshot

<img width="450" alt="QR Code Generator Screenshot" src="https://github.com/user-attachments/assets/12b96256-7d6e-4a39-8ae3-fc18b2cdaee8">

## 🔧 How It Works

The application uses the [QR Server API](https://api.qrserver.com/) to generate QR codes. When a user enters text or a URL, the application:

1. Validates the input to ensure it's not empty
2. Constructs an API request URL with the input data
3. Generates and displays the QR code image
4. Provides visual feedback through smooth animations

## 📝 License

This project is open source and available for educational purposes.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
