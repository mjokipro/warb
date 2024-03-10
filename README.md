# warb

An application used to display Twitter Clone project for Matthew Joki, built with Flask / Python, Jinja2, SQLAlchemy, and Postgresql.

# Installation and Setup Instructions

Clone this repository. You will need Python 3 installed globally on your machine.

## Installation:

pip install -r requirements.txt

## To Run Test Suite:

python3 unittest

## To Start Server:

python3 app.py

## To Visit App:

localhost:5000/

# Reflection
The drive for this project was to create an innovative Twitter Clone project using the learned skills from the Software Engineering curriculum at Auburn University.
I set out to build only a basic CRUD app.
This project was challenging because it provided the opportunity to gain experience using this new skill.
An unexpected obsticle that I encountered was during deployment.  I had to conduct extensive research to discover how to properly deploy using Gunicorn on Render.com.
I used Flask / Python, Jinja2, SQLAlchemy, and Postgresql to complete this project.

Example:
This was a week long project built during my third module at Auburn. Project goals included using technologies learned up until this point and familiarizing myself with documentation for new features.

Originally I wanted to build an application that allowed users to pull data from the Twitter API based on what they were interested in, such as 'most tagged users'. I started this process by using the create-react-app boilerplate, then adding react-router-4.0 and redux.

One of the main challenges I ran into was Authentication. This lead me to spend a few days on a research spike into OAuth, Auth0, and two-factor authentication using Firebase or other third parties. Due to project time constraints, I had to table authentication and focus more on data visualization from parts of the API that weren't restricted to authenticated users.

At the end of the day, the technologies implemented in this project are React, React-Router 4.0, Redux, LoDash, D3, and a significant amount of VanillaJS, JSX, and CSS. I chose to use the create-react-app boilerplate to minimize initial setup and invest more time in diving into weird technological rabbit holes. In the next iteration I plan on handrolling a webpack.config.js file to more fully understand the build process.
