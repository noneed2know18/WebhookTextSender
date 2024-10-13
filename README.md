# WebhookTextSender

**WebhookTextSender** is a Python script for sending text messages through Discord webhooks. It provides a straightforward command-line interface to manage webhook settings and send messages, with options for customization and feedback.

(https://guns.lol/noneed2know)

## Features

- **Configure Webhook Settings**: Set or modify the webhook URL, username, and avatar URL.
- **Customize Success Messages**: Choose the color for success messages and receive clear feedback after sending messages.
- **Send Messages**: Post text messages to a specified Discord webhook and get real-time feedback on the success or failure of the operation.
- **Terminal Management**: Clear the terminal for better readability after modifying settings.

## Requirements

- Python 3.x
- Requests library
- Colorama library

## Installation

1. **Clone the repository** (if applicable):

    ```bash
    git clone https://github.com/yourusername/WebhookTextSender.git
    cd WebhookTextSender
    ```

2. **Install the required libraries**:

    ```bash
    pip install requests colorama
    ```

## Usage

1. **Run the script**:

    ```bash
    python webhook_text_sender.py
    ```
    
    or
   
    ```bash
    python3 webhook_text_sender.py
    ```

3. **Configure Settings**:
    - Enter `settings` to modify webhook parameters (URL, username, and avatar URL). The terminal will be cleared after updating any parameter.

4. **Send a Message**:
    - Enter your text message to send it via the configured webhook.

5. **Modify Parameters**:
    - Choose from the menu options to update the webhook settings. The terminal will be cleared after each modification.

## Example

Here’s how you might interact with the script:

```plaintext
Enter the message to send (or 'settings' to modify settings): Hello, world!
[14:23:45] Message sent successfully
