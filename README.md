<h1>Blog posting site</h1>
![Screenshot 2024-12-08 132450](https://github.com/user-attachments/assets/904c992d-b0bc-4f66-99b2-fb837bafe0ea)

<h2>This project was made to display my skills with frontend and backend programming to construct a full stack web application.</h2>

I used flask as the server for the site and css, bootstrap and javascript for the styling and responsivity of the website. The website allows the admin user (The first user to register to the site), to create blog posts, edit posts and delete posts whenever they wish. I used flask login authenticator to authenticate users, when a user registers their email and name is stored in the SQLite database and their password is hashed and salted using the werkzeug security package. When a user then wants to login using their username and password, the password is hashed and salted again then compared with the corresponding email's password in the database and if they match then the user is authenticated. Any user that is registered and logged in can then comment on posts 
