# QR Code Generator

A simple and user-friendly web application built with **Flask** that generates QR codes instantly from any text, URL, or other input provided by the user.

## Features

* Generate QR codes from text or URLs
* Simple and clean web interface
* Instant QR code generation
* Automatically saves the generated QR code image
* Lightweight and easy to run locally

## Tech Stack

* **Backend:** Flask (Python)
* **Frontend:** HTML, CSS
* **Library:** qrcode, Pillow

## Project Structure

```
QR_Code_Generator/
│
├── app.py
├── requirements.txt
├── static/
│   └── qr.png
├── templates/
│   └── index.html
└── README.md
```

## How to Use

1. Open the application in your browser.
2. Enter any text or URL.
3. Click the **Generate QR Code** button.
4. The generated QR code will be displayed on the page and saved in the `static` folder as `qr.png`.

## Requirements

* Python 3.8 or later
* Flask
* qrcode
* Pillow

## Future Enhancements

* Download QR code directly
* Customize QR code colors
* Change QR code size
* Add logo inside the QR code
* Generate QR codes in multiple image formats
* Maintain a history of generated QR codes

## Author

**Hafees Muhammed V A**

B.Tech in Artificial Intelligence & Data Science

**Just try out my project:**https://qr-code-generator-tool.onrender.com
