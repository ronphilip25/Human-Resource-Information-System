# Human Resource Information System (HRIS)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
The Human Resource Information System (HRIS) is a comprehensive solution designed to manage various HR functions such as employee data management, attendance tracking, payroll processing, and more. This system is built using a modern tech stack to ensure efficiency, scalability, and a great user experience.

## Features
- Employee management
- Attendance tracking
- Role-based access control
- Reporting and analytics

## Tech Stack
- **Python**: Programming language used for backend development.
- **Django**: Web framework used for building the server-side logic.
- **Tailwind CSS**: Utility-first CSS framework used for styling.
- **JavaScript**: Programming language used for frontend interactivity.
- **HTML5**: Markup language used for structuring the web pages.
- **CSS**: Style sheet language used for describing the presentation of web pages.

## Installation
Follow these steps to set up the project locally:

1. **Clone the Repository**

    ```bash
    git clone https://github.com/ronphilip25/HRIS-Design.git
    cd HRIS-Design
    ```

2. **Create and Activate a Virtual Environment**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Dependencies**

    ```bash
    pip install -r requirements.txt
    ```

4. **Apply Migrations**

    ```bash
    python manage.py migrate
    ```

5. **Run the Development Server**

    ```bash
    python manage.py runserver
    ```

6. **Open Your Browser**

    Open your browser and go to `http://127.0.0.1:8000` to see the application in action.

## Usage
- **Admin Interface**: Access the Django admin interface at `http://127.0.0.1:8000/admin` to manage HR data.
- **Employee Dashboard**: Employees can log in to view and manage their information.

## Contributing
We welcome contributions to enhance the HRIS system. To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact
For any questions or suggestions, please feel free to reach out to the project maintainer:

- **Name**: Ron Philip
- **Email**: sanchezronphilip@gmail.com

---

Thank you for using the HRIS system! We hope it meets all your HR management needs.
