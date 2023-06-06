# WhatsApp Automation with Python and Selenium

This repository contains a Python script that automates the process of sending messages on WhatsApp using Selenium. By leveraging the power of Selenium's web automation capabilities, you can easily send multiple messages to contacts without the need for manual intervention.

## Features

- Compatible with all devices and screen resolutions
- Seamless integration with WhatsApp Web
- Ability to send messages to contacts in your WhatsApp contacts list
- Customizable message content
- Option to specify the number of times a message should be sent

## Prerequisites

Before running the script, ensure you have the following:

- Python installed on your system
- Selenium Python library (`selenium`) installed
- Microsoft Edge web browser installed
- Microsoft Edge WebDriver executable compatible with your Microsoft Edge browser version

## Setup Instructions

1. Clone this repository to your local machine or download the script file.
2. Install the required dependencies by running the following command:
   ```
   pip install selenium
   ```
3. Download the appropriate Microsoft Edge WebDriver executable for your Microsoft Edge browser version from the [Microsoft Edge WebDriver downloads page](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/).
4. Place the downloaded Microsoft Edge WebDriver executable in the same directory as the script file.
5. Run the script using the following command:
   ```
   python whatsapp_automation.py
   ```

## Usage

1. After running the script, a Microsoft Edge window will open with WhatsApp Web.
2. Scan the QR code displayed on the screen using your mobile device to log in.
3. Once logged in, the script will prompt you to enter the name of the contact to whom you want to send the message. Note that the name must exist in your WhatsApp contacts list.
4. Enter the desired message content when prompted.
5. Specify the number of times you want the message to be sent.
6. The script will then automate the process of sending the specified number of messages to the specified contact.

## Disclaimer

This script is intended for educational and personal use only. Use it responsibly and respect WhatsApp's terms of service. The developer assumes no responsibility for any misuse or violation of WhatsApp's policies.
