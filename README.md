# LinkHub

LinkHub is a customizable homepage for your browser that allows you to easily manage your most-visited links through interactive buttons. You can add, edit, delete, and reorder buttons with ease. All configurations are saved locally, with the option to export and import settings, making it simple to transfer your setup across devices.

## Features

* **Customizable Buttons:** Add, edit, and delete buttons with custom text, link URLs, and colors.
* **Drag-and-Drop Reordering:** Organize your buttons by dragging and dropping them.
* **Title Customization:** Edit the homepage title directly from the UI.
* **Save & Load Configuration:** Export your configuration to a JSON file for backup or use on another device.
* **Cross-Device Access (Future Feature):** Planned integration with Box Drive for network-wide access and portability.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/pbeens/LinkHub.git
   ```

2. Navigate to the project directory:

   ```bash
   cd LinkHub
   ```

3. Open the `my-homepage.html` file in your preferred browser:

   ```bash
   open my-homepage.html
   ```

## Usage

* **Adding a Button:** Click the `Add New Button` button and fill in the details.
* **Editing a Button:** Click the edit icon on any button to modify its text, link, or color.
* **Deleting a Button:** Use the `Delete Button` option inside the edit menu.
* **Reordering Buttons:** Drag and drop buttons to change their order.
* **Saving Configuration:** Click `Save Configuration` to export your setup as a JSON file.
* **Loading Configuration:** Click `Load Configuration` and select a previously saved JSON file.

## Configuration File

The configuration is stored in a JSON format. A sample configuration (`default.json`) is included:

```json
{
    "title": "My Homepage",
    "buttons": [
        {
            "text": "Google Search",
            "link": "https://www.google.com",
            "color": "Blue"
        },
        {
            "text": "Bing Search",
            "link": "https://www.bing.com",
            "color": "Green"
        }
    ]
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Future Enhancements

* **Box Drive Integration:** Save configuration to Box Drive for network-wide access.
* **Responsive Mobile View:** Optimize the interface for mobile and tablet devices.
* **Cloud Sync:** Option to sync configurations through cloud storage.

