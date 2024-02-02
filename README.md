# ctrip
cTrip Crypto Payment Gateway: Flask-based solution for Crypto payments. Features include automatic payment checking, Securely stores data in a JSON database. Ideal for businesses embracing cryptocurrency transactions.

![Project Image](ctrip.png)

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

## Overview

The cTrip Crypto Payment Gateway is a Flask-based solution for integrating cryptocurrency payments, specifically leveraging Ethereum blockchain technology. This project simplifies the generation of unique payment addresses, automatic payment checking, and admin notifications.

## Key Features

- **Ethereum Integration:** Utilizes Web3.py for Ethereum blockchain interaction.
- **Automatic Payment Checking:** Background tasks automatically check payment statuses.
- **Dark Theme and Responsive UI:** Styled with Bulma for a visually appealing and responsive user interface.
- **JSON Database Storage:** File-based JSON database for secure storage and retrieval of payment information.
- **Admin Notification:** Automatically sends payment information to an admin address.

## Getting Started

1. Clone the repository: `git clone https://github.com/yourusername/ctrip-crypto-payment-gateway.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Configure Ethereum settings, Infura API, and admin addresses in the code.
4. Run the Flask application: `python app.py`

## Usage

- **Generate Payment Address:** Access `/generate_payment_address` for a unique payment address and private key.
- **Check Payment Status:** Use `/check_payment/<payment_address>` to verify payment status.
- **Admin Notification:** Successful payments trigger automatic notifications to an admin address.

## Contributing

Contributions are welcome! Feel free to open issues, suggest improvements, or submit pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

