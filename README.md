## Tech Stack :
* React, Express, NodeJS, CSS, JavaScript, Socket.io

## Features :
* Real time functioning through Socket.io since HTTP requests, though good for serving up websites, are slow.
* Used query strings - retreive data from URL and not through props or Redux
* Displays the Active users in any particular given room
* Emoji conversion from characters to actual emojis using react-emoji [eg :) ]

## Setup : 
1. Install the Public Dependencies and express mongoose nodemon socket.io bcrypt cors dotenv on server side.
2. In the Server Directory there's a .env file. Change the value of mongodb inside the file. Set the value as your mongodb connection url.
3. Now start the server by yarn start and then start the react by yarn start
4. And the chat application would be running successfully by now.

### Register Page
<img width="564" alt="Register" src="https://user-images.githubusercontent.com/63936863/175763478-6eaca05b-642d-4837-a526-c0fb49fd87d9.png">

### Login Page
<img width="574" alt="Login" src="https://user-images.githubusercontent.com/63936863/175763649-8e414cde-9f71-42bd-a975-5437c9cd0e40.png">

### Chat WebPage
<img width="711" alt="WebApp" src="https://user-images.githubusercontent.com/63936863/175763668-c43b39ef-d038-4051-a873-346a3b4fe563.png">





