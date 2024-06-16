## Desktop Automation Setup
Overview

This script automates the process of setting up your desktop environment by opening necessary applications and logging into accounts. It uses pyautogui for GUI automation and dotenv for environment variable management.

## Prerequisites

Python 3.x
pyautogui library
python-dotenv library

## Setup
Install the required libraries:
pip install
pyautogui
python-dotenv
opencv
pillow

Create a .env file in the same directory as your script with the following content:

NOTION_PASSWORD= your_notion_password
GOOGLE_PASSWORD= your_google_password

Replace your_notion_password and your_google_password with your actual passwords.

## Usage

Run the script using Python:

python desktop_setup.py

Ensure that images used for clicks_image() function are present in the working directory.
