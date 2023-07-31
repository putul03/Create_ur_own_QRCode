# QR Code Generator

This Python script generates a QR code for a given URL. The QR code contains a link to my LinkedIn profile.

## Introduction

QR Code Generator is a simple Python script that utilizes the `qrcode` library along with `PIL` (Python Imaging Library) to generate a QR code for a specified URL. The script creates a QR code containing the link to my LinkedIn profile, but you can easily modify it to generate QR codes for any URL you want and also perform the changes for border, qr size and colors according to your need.

## Requirements

To run the QR Code Generator, you need the following dependencies:

- Python (3.x recommended)
- qrcode library
- Python Imaging Library (PIL)

## Installation

1. Make sure you have Python installed. If not, download and install it from the official website: [Python.org](https://www.python.org/downloads/)

2. Install the required libraries by running the following command in your anaconda prompt:

   ```bash
   pip install qrcode
   conda install -c conda-forge pillow
   ```

## Usage

1. Clone this repository to your local machine or simply download the `qr_code_generator.py` file.

2. Open a terminal or command prompt and navigate to the directory where `qr_code_generator.py` is located.

3. Execute the script by running the following command:

   ```bash
   python qr_code_generator.py
   ```

4. The script will generate a QR code and display it using your default image viewer. The QR code will also be saved as `qr_code.png` in the same directory.

5. Customize the script by modifying the URL inside the `qr.add_data()` method. Replace it with the URL you want to create a QR code for.

Please make sure to replace `qr_code_generator.py` with the actual name of your Python script if it's different. Additionally, create a `LICENSE` file in your repository if you haven't already, and choose an appropriate open-source license for your project.

Generate your own qrcode happily and easily!
