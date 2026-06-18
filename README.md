# Air Force Shipment Manager (AFSM)

## Overview

The Air Force Shipment Manager (AFSM) is a web application designed to help users manage and prepare hazardous materials for shipment. It provides detailed guidelines sourced from AFMAN 24-604, including a comprehensive list of items, their UN/ID numbers, and their proper shipping names/descriptions.

## Features

* **Hazardous Material Preparation Guide:** AFSM provides a step-by-step guide to preparing various hazardous materials for shipment. It includes attachments covering a wide range of topics such as item listing, different types of hazardous materials, certifying hazardous materials, and more.

* **Unit Conversion Tool:** AFSM includes a comprehensive unit conversion tool to help users convert between different units of volume, weight, length, and force.

* **Substance Listing:** The application provides a detailed listing of various substances along with their UN/ID numbers and proper shipping names/descriptions.

## Running Locally

Clone the repository, install the Django dependencies, and run the development server:

```bash
python manage.py migrate
python manage.py runserver
```

Then open `http://127.0.0.1:8000/` in your browser.

## Technology Stack

AFSM is built using the following technologies:

* Backend Framework: Django
* Frontend Framework: Django Bootstrap
* Database: SQLite

## Limitations

* No User Login: Currently, the application does not include user login functionality. Users can access the application and its features without authentication.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contact

If you have any questions or inquiries about this project, you can reach out to the project maintainer at [xinyiklin@gmail.com](mailto:xinyiklin@gmail.com).
