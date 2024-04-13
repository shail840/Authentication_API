# Project: Authentication and Validation in DRF

## Overview
This project focuses on implementing authentication and validation mechanisms within Django Rest Framework (DRF). It involves adding form validators to form data, performing token and session authentication, and utilizing popular packages like Djoser and authtoken for default routes. Additionally, the Django admin panel is used for user and token management.

## Key Features
1. **Authentication Mechanisms**: The project utilizes DRF's authentication system to ensure secure access to APIs.
2. **Validation Enhancements**: Form validators are added to validate form data, enhancing data integrity and security.
3. **Token and Session Authentication**: Both token and session authentication methods are employed to authenticate users.
4. **Package Integration**: Djoser and authtoken packages are integrated to streamline the authentication process and provide default routes.
5. **Admin Panel Usage**: The Django admin panel is leveraged for efficient creation and management of users and tokens.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/shail840/Authentication_API.git

    ```
   
2. Install Pipenv (if you haven't already):

    ```
    pip install pipenv
    ```

3. Install dependencies using Pipenv:

    ```
    pipenv install
    ```

4. Activate the Pipenv shell:

    ```
    pipenv shell
    ```


5. Run the development server:

    ```
    python manage.py runserver
    ```
6. Access the API using:- http://127.0.0.1:8000/api/ratings

7. Use Insomnia for testing the API.
## Concluding Notes
This project demonstrates the importance of implementing robust authentication and validation mechanisms in web applications, particularly when dealing with sensitive user data. By leveraging DRF and related packages, developers can ensure a secure and seamless user experience.

## Contributing

Contributions to the API are welcome! If you would like to contribute to the project, please fork the repository, make your changes, and submit a pull request.

## Contact

For questions or feedback regarding Authentication_API, please contact at [shailendrapal840@gmail.com](mailto:shailendrapal840@gmail.com).
