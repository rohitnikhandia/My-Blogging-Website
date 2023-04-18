# My Blogging Website
Welcome to my blogging website, built using Python, Django framework, HTML, CSS, Django ORM, and Django templating language, with SQLite database. This website is designed for bloggers who want to share their thoughts and ideas with the world. It includes a profile section where users can update their profiles and posts, and user authentication and authorization for secure access.

## Features
* User registration and authentication: Allow users to create accounts and log in securely to access the site's features.
* User profiles: Provide users with a profile page where they can customize their profiles, add a profile picture, and write a brief bio.
* Blog post creation and management: Allow users to create, edit, and delete blog posts on the site.
* Security: Implement appropriate security measures to protect user data and prevent unauthorized access to the site.

## Installation
To install this project on your local machine, please follow these steps:

### 1. Clone the repository:
```
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```
### 2. Navigate to the project directory:
```
cd YOUR-REPOSITORY
```

### 3. Install the required packages:
```
pip install -r requirements.txt
```

### 4. Create the SQLite database:
```
python manage.py migrate
```
### 5. Run the server:
```
python manage.py runserver
```

## Usage
Once the server is running, open a web browser and go to http://127.0.0.1:8000/ to access the website. Use the following endpoints to access the different features:

* /login/: Login page for existing users.
* /logout/: Logout page for logged-in users.
* /password_reset/: Password reset page for users who have forgotten their password.
* /register/: Registration page for new users.
* /profile/: User profile page where users can update their personal details and posts.
* /user/<str:username>/: User profile page for a specific user.
* /post/<int:pk>/: Blog post detail page.
* /post/new/: Create a new blog post page.
* /post/<int:pk>/update/: Update an existing blog post page.
* /post/<int:pk>/delete/: Delete an existing blog post page.
* /about/: About page for the website.

## Contributing
This project is open-source and contributions are welcome. To contribute, please fork the repository and submit a pull request with your changes.
