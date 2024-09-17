# Job Application Form

This Django application allows users to submit a job application. The application form collects basic information such as the user's name, email address, date of birth, and occupation. Once the user submits the form, the data is stored in a database and an email confirmation is sent to the user.

## Features

* Collects basic user information
* Stores data in a database
* Sends email confirmation to users
* Uses Bootstrap for styling
* Includes an admin interface

## Installation

1. Clone the repository: `git clone https://github.com/username/job-application-form.git`
2. Create a virtual environment: `python3 -m venv venv`
3. Activate the virtual environment: `source venv/bin/activate`
4. Install the required packages: `pip install -r requirements.txt`
5. Create a `.env` file and add the following environment variables:
    * `EMAIL_HOST`
    * `EMAIL_PORT`
    * `EMAIL_USE_TLS`
    * `EMAIL_HOST_USER`
    * `EMAIL_HOST_PASSWORD`
6. Run the application: `python manage.py runserver`

## Usage

1. Visit the application at `http://localhost:8000/`
2. Fill out the job application form
3. Click the "Submit" button
4. You will receive an email confirmation with your application details

## Admin Interface

To access the admin interface, follow these steps:

1. Create a superuser account: `python manage.py createsuperuser`
2. Visit the admin login page at `http://localhost:8000/admin/login/`
3. Enter your superuser credentials and click the "Log in" button

Once you are logged in to the admin interface, you will be able to view, edit, and delete job applications. You can also add new users and change their permissions.

## Contributing

1. Fork the repository
2. Create a new branch for your changes
3. Make your changes
4. Commit your changes
5. Push your changes to your fork
6. Create a pull request


