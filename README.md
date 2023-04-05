# Little Lemon Bistro

Little Lemon Bistro is a Django web application for a restaurant. It allows users to view the menu, book a table, and learn more about the restaurant.

### Features

- Home page with restaurant information
- Menu page displaying a list of menu items
- Menu item details page with images and descriptions
- Table booking form
- About page with the restaurant's story and contact information

### Getting Started

These instructions will help you set up the project on your local machine for development and testing purposes.

### Prerequisites

- Python 3.6 or higher
- Django 3.2 or higher
- SQLite (included with Django)

### Installation

1. Clone the repository.

        git clone https://github.com/yourusername/little-lemon-bistro.git

2. Change into the project directory.

        cd little-lemon-bistro

3. Create a virtual environment and activate it.

        python3 -m venv venv
        source venv/bin/activate

4. Install the required dependencies.

        pip install -r requirements.txt

5. Apply database migrations.

        python manage.py makemigrations
        python manage.py migrate

6. Create a superuser to manage the admin site.

        python manage.py createsuperuser

Follow the prompts to provide a username, email, and password.

7. Run the development server.

    python manage.py runserver

8. Open your web browser and visit http://127.0.0.1:8000/ to see the application.

9. Access the admin site at http://127.0.0.1:8000/admin/ and log in with the superuser credentials you created earlier. Here, you can manage the menu items and bookings.

