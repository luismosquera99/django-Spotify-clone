# Spotify Clone Project

## Table of Contents
1. Introduction
2. Technologies Used
3. APIs Used
4. Setup and Installation
5. Deployment
6. Contributing
7. License

## Introduction
This project is a clone of the popular music streaming service, Spotify. It aims to replicate the core features of Spotify while also providing a platform for learning and experimenting with various technologies.

## Technologies Used
- **Python**: The backend of the application is written in Python, a powerful, flexible language that is great for web development.
- **Django**: Django is a high-level Python web framework that encourages rapid development and clean, pragmatic design.
- **Virtual Environment**: A virtual environment is used to manage the dependencies of the project, ensuring that it remains clean and organized.
- **Tailwind CSS**: Tailwind CSS is a utility-first CSS framework that is used for styling the frontend of the application.
- **PostgreSQL**: PostgreSQL is a powerful, open-source object-relational database system that is used as the primary database for the project.
- **AWS**: Amazon Web Services (AWS) is used for database hosting, providing a reliable and scalable solution for database management.
- **Other Libraries**: Various other Python libraries are used in the project to provide additional functionality.

## APIs Used
- **Spotify Scrapper API**: This API, available through RapidAPI, is used to fetch all the data and endpoints for the project.
- Note: This API used to be fully free, now is 'Freemium' so some endpoints would not work unless you pay a suscription. 

## Setup and Installation
1. Clone the repository to your local machine.
2. Set up a virtual environment using `venv` and activate it.
3. Install the dependencies using `pip install -r requirements.txt`.
4. Set up the PostgreSQL database and note down the credentials.
5. Create a `.env` file in the root directory and add the database credentials.
6. Run the Django migrations using `python manage.py migrate`.
7. Start the server using `python manage.py runserver`.

## Deployment
The project is deployed using Zeet with AWS Lambda. To deploy your own version of the project:
1. Set up an account on Zeet.
2. Connect your GitHub account and select the repository.
3. Configure the build settings according to your project.
4. Click on 'Deploy' and wait for the process to complete.

## Contributing
Contributions to this project are welcome. Please fork the repository, make your changes, and submit a pull request.
