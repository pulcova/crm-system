# Customer Relationship Management using Django

This project is a Customer Relationship Management (CRM) system built with Django, a high-level Python web framework. It allows businesses to manage interactions with their customers, including storing customer information, tracking interactions, and managing sales leads.

## Requirements

- Python 3.2x or later must be installed on your system.
- Create a virtual environment using Python 3.2x and activate it.

python3.2 -m venv venv_name
source venv_name/bin/activate # For Linux/Mac
venv_name\Scripts\activate.bat # For Windows

- Install project dependencies listed in `requirements.txt`:

pip install -r requirements.txt

## Usage

1. Create a superuser to access the Django admin panel:

python manage.py createsuperuser

Follow the prompts to create a username, email, and password for the superuser.

2. Apply database migrations:

- To create migrations:
  ```
  python manage.py makemigrations
  ```
- To apply migrations:
  ```
  python manage.py migrate
  ```

3. Run the development server:

python manage.py runserver

Access the CRM application at `http://127.0.0.1:8000/` in your web browser.

## Django Superuser

To create a superuser in Django, use the `createsuperuser` management command. It prompts you to enter a username, email address, and password for the superuser account. The superuser has access to the Django admin panel, where you can manage users, groups, and other site settings.

## Database Migrations in Django

Database migrations are used to propagate changes you make to your models (adding a field, deleting a model, etc.) into your database schema. To create migrations, use the `makemigrations` management command, and to apply migrations, use the `migrate` command.

For more information on Django commands and usage, refer to the [Django documentation](https://docs.djangoproject.com/en/stable/).
