# Amazon Order Tracking Extractor

**Amazon Order Tracking Extractor** is a Chrome extension designed to help Amazon sellers easily extract tracking numbers from Amazon Seller Central orders. The extension automatically retrieves tracking numbers from order pages, displays them in a user-friendly table, and allows users to copy the results for use in tools like Google Sheets.

## Features

- Extract tracking numbers directly from Amazon Seller Central order pages.
- View the extracted tracking numbers in an easy-to-read table.
- Copy all tracking numbers to your clipboard with a single click.
- Automatically close tabs after extraction.
- Receive alerts when all orders have been processed.

## How It Works

1. **Ensure you are logged in to Amazon Seller Central.**
2. Open the extension from the Chrome toolbar.
3. Enter the order IDs in the textarea (one order ID per line).
4. Click the **Start Extraction** button.
5. The extension will open new tabs, extract the tracking numbers, and display them in a table.
6. Once all orders have been processed, an alert will appear.
7. Click **Copy Tracking Numbers** to copy the extracted data in a format ready for Google Sheets.

![Screenshot](screenshots/screenshot2.png)

## Installation

1. Download the extension from the [Chrome Web Store](#).
2. After installation, click on the extension icon in the Chrome toolbar.
3. Follow the steps listed above to extract tracking numbers.

## Permissions Justification

- **Tabs**: Required to open new tabs for accessing Amazon Seller Central order pages and extracting tracking numbers.
- **Scripting**: Injects a content script to extract the tracking numbers from the order pages.
- **Storage**: Temporarily stores the extracted tracking numbers during the session.
- **Host Permissions**: Allows access to Amazon Seller Central to retrieve tracking numbers.

## Privacy Policy

This extension does not collect, store, or share any personal data. All information processed by the extension remains locally on your machine. You can view the full privacy policy [here](https://<your-github-username>.github.io/amazon-order-extractor-privacy-policy/privacy-policy.html).
