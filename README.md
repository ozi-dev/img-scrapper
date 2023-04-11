
# Image Scraping Google Images using Selenium and Python

This is a Python code that allows you to scrape multiple image URLs of a particular keyword from Google via web scraping. The code will open up a headless Chrome browser instance to fetch the images.

## Prerequisites

Before running this code, make sure to install the following:

- **Google Colab:** In order to run the code, import the required libraries and modules in Python, and connect to the cloud platform.
- **Chromium Browser and Driver:** You need to download and install Chromium browser and driver, which are necessary for Selenium to execute browser commands on Chrome browser.
- **Selenium:** Install the selenium library to enable browser automation and interaction with the web page.
- **Pillow (Python Imaging Library):** This is a library that adds support for opening, manipulating, and saving many different image file formats in Python.

## How to Use

* Import the required libraries and modules in Python and mount to your Google Drive by running drive.mount('/content/drive') command.
* The code will then download the necessary files to install Chromium and its related components on Ubuntu. Note that Ubuntu no longer distributes chromium-browser outside of snap.
* After installing Chromium, the code will install selenium and create an instance of webdriver that will be used to control the headless Chrome browser.
* Modify the driver.get(url.format(s='YOUR İMAGE KEYWORD')) line to enter your desired image search keyword.
* Run the code, and it will fetch up to 400 image URLs of the specified keyword from Google Images.
* Once the code has finished executing, the fetched images can be found at the path specified in the code. If the path was not specified, they will be saved in the default path.
## Author Information
This code was created by Oğuzhan Öztürk, for further information: oguzhanozturk0@outlook.com
