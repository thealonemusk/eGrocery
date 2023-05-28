# eGrocery
Prerequisites
Before you proceed with the installation, make sure you have the following prerequisites installed on your system:

Python 3.x: Make sure you have Python 3.x installed on your machine.
pip: Python package installer. You can check if it's installed by running pip --version in the command line.
Installation
To set up the Grocery Website project, follow these steps:

Clone the repository: git clone <repository_url>
Navigate to the project directory: cd grocery-website
Install project dependencies: pip install -r requirements.txt
Set up the database:
Create a PostgreSQL database for the project.
Update the database configuration in the settings.py file.
Apply database migrations: python manage.py migrate
Create a superuser account: python manage.py createsuperuser
Follow the prompts to set a username and password for the superuser account.
Collect static files: python manage.py collectstatic
Run the development server: python manage.py runserver
Congratulations! The Grocery Website should now be up and running on your local machine.

Usage
To access and use the Grocery Website, open a web browser and go to http://localhost:8000/. From there, you can navigate through the different pages, search for products, add items to the cart, and proceed with the checkout process.

To access the admin dashboard, go to http://localhost:8000/admin/ and log in using the superuser account credentials you created during the installation process. The admin dashboard provides access to various management functionalities for products, categories, users, and orders.

Contributing
We welcome contributions to enhance the Grocery Website project. If you would like to contribute, please follow these steps:

Fork the repository on GitHub.
Create a new branch from the main branch.
Make your modifications and additions.
Test your changes to ensure they work correctly.
Commit and push your changes to your forked repository.
Submit a pull request to the original repository



