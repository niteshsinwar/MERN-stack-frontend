# MERN stack frontent
This is a sample restaurant website built using React and Bootstrap. It includes pages for home, about, menu, contact, and a favorites page that requires authentication. Users can view the featured dishes on the home page, view the menu items and details, submit feedback, add and remove items from their favorites list, and log in and out.
<br>
The website is built using React, React-Bootstrap, React-Router, Redux, and json-server for the backend. The authentication is handled using jsonwebtoken and the json-server-auth package. The website is fully responsive and adapts to different screen sizes.

## Getting started
To run this project, follow these steps:

- Clone this repository onto your local machine.
- Install the required dependencies by running npm install in the project directory.
- Start the json-server backend by running json-server --watch db.json --port 3001 --host 0.0.0.0 in a separate terminal window in the project directory.
- Start the development server by running npm start in the project directory.
- Open http://localhost:3000 in a web browser to view the website.
## Features
- Home page: displays featured dishes and promotions
- Menu page: displays all menu items and their details
- Contact page: allows users to submit feedback
- Favorites page: displays the user's favorite dishes and allows them to add and remove dishes from their favorites list (requires authentication)
- Authentication: users can log in and out to access the favorites page
-Fully responsive design: adapts to different screen sizes
## Credits
This project was built as part of the Full-Stack Web Development with React specialization on Coursera. The project structure, styles, and starter code were provided by the course instructors. The functionality and authentication features were added by me.
