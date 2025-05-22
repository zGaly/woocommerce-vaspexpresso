# WooCommerce VaspExpresso Plugin

This repository provides the public documentation for the **VaspExpresso WooCommerce Plugin**, which integrates WooCommerce with the VaspExpresso logistics system.

> **Note:** The source code is private and not included in this repository.

---

## Features

- **Direct Integration with VaspExpresso API**
  - Automatically create shipping services based on order status.
  - Full support for multiple service types: VASP24, VASPDOM, KIOSK, Madeira, Azores, etc.

- **Pickup Point Selection**
  - Allow customers to select nearby pickup points during checkout.
  - Compatible with both Classic and Block-based Checkout.
  - Validates selected points as required.

- **Label Generation**
  - Generate shipping labels from the order admin panel.

- **Shipment Tracking**
  - Track orders with direct tracking links provided to the customer.

- **Return Management**
  - Generate return shipments using the PickAndReturn option.

- **Flexible Service Configuration**
  - Choose and activate any available VaspExpresso shipping method.

- **Support for Virtual Products**
  - Configure whether virtual products are allowed in VaspExpresso shipments.

- **Free Shipping Threshold**
  - Set a minimum order amount for activating free shipping.

- **Admin Configuration Panel**
  - Define API credentials for sandbox and production.
  - Set sender information (name, phone, address, etc.).
  - Select which order statuses trigger service creation or cancellation.
  - Enable or disable specific service types.
  - Optional debug log for troubleshooting.

---

## Requirements

- PHP 7.0 or higher  
- WordPress 5.0 or higher  
- WooCommerce 7.x or higher  
- Active VaspExpresso account with API access  

---

## FAQ

**Do I need a VaspExpresso account?**  
Yes. You need valid API credentials provided by VaspExpresso.

**Is the plugin compatible with Block-based Checkout?**  
Yes, fully supported from version 1.2.1 onwards.

**Can I use it with virtual products?**  
Yes. You can configure whether virtual products are allowed in orders with VaspExpresso shipping.

**How do I track shipments?**  
Tracking links are available in order details and email notifications.

**Can I create return shipments?**  
Yes. From the admin order page, use the “Request Return Service” action for cancelled orders with an existing shipment.

**Which service types are supported?**  
All available from VaspExpresso: VASP24, VASPDOM, VASP48, KIOSK, Azores, Madeira, and more.

**How do I debug API issues?**  
Enable debug logging in the plugin settings. Logs are saved to `wp-content/debug.log`.

---

## Changelog

See the full changelog in the `readme.txt` or plugin documentation.  
Highlights from the latest versions include:

- Enhanced address handling for KIOS orders
- Improved validation for service creation
- Better debug logging and transient caching
- Block checkout translation fixes and AJAX support

---

## License

This plugin is proprietary and not open-source.  
All rights reserved © [Comsoftweb].

Licensed under [GPL-2.0+](http://www.gnu.org/licenses/gpl-2.0.txt)
