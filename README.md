# My biggest web project
![](readmeAsset/dating1.gif)
## How long did it take ?
24 days

## challenge accepted ?
- [x] a loooooooooooot of features done in a small amount of times
- [x] team project (coordination is key to success)
- [x] learn react and node in one week
- [x] own local webserver using docker compatible with any os
- [x] no security breaks


## What did I learn ?
  * react.js
  * redux
  * node.js
  * bootstrap and templating
  * socket.io
  * sorting and filtering lot's of data
  * implementing working UI fast with react
  * creating a seed of random users to test the app
  * working very fast with deadlines
  * working with team mates


![](readmeAsset/connect.gif)

## What is this project ?
This is a dating app that has 4 main features :

### 1. User Features
A user can register. A mail of confirmation is send to validate his registration. A user can login. A user can modify his information and password once login. A user can reset his password if he forgets it with his mail address. A user can : upload photos, define a profile picture, define his bio, define his age, define his sex and sexual orientation, define tags to better describe him and others...
![](readmeAsset/profile.gif)

### 2. Matching and Public Profiles of other Users
A selection of user profiles is proposed to the connected user according to his parameters (sex, geographic proximity, interests in common, fame score). He can click on each users to consult their profiles. Each profile is likable, blockable, reportable and dislikable.
![](readmeAsset/search.gif)

### 3. Search Engine (sorting and filtering)
You can search for specific user according to specific tags, geographic proximity, age and fame. You can also sort the selection through these properties.

### 4. Notifications and Chat
Once two users have liked each other (match) their pictures appear in the user selection of the chat page and they can exchange messages (they can chat).
Notification system is in place : a user receives a notification if : 
  * a user consult your profile
  * a user likes your profile
  * a user sends you a message
  * a user dislike your profile
![](readmeAsset/chat.gif)
For more information about the project please see the pdf subject available in french and english at ![subject](https://github.com/nepriel/site-de-rencontre/tree/master/subject "subject").

### How do I run it on my laptop ?
You will need docker running on your machine.


####Setup the environement varibales

- Within the root path 

```bash
# environment variables
cp .env-template .env
```

- Navigate to /backend path 

```bash
# environment variables
cp .env-template .env
```

- Navigate to /frontend path 

```bash
# environment variables
cp .env-template .env
```

####Build the containers

In the root path

```bash
docker-compose up --build
```

Note : the port 80 must not be used by another application (like Apache or Skype).

P.S : The build may take some time don't worry be happy and grab a cup of tea :)

Once the containers started.
Navigate to frontend to start the server.

```bash
npm start
```
P.S : npm version 6.7.0


####List of links

```bash
si.matcha.local:3000 -> backend ( REST API )
app.matcha.local:8083 -> frontend
phpmyadmin.matcha.local:8080 -> phpMyAdmin
```

![alt text](https://github.com/nepriel/instagram-42/blob/master/hello.PNG "result of evaluation of project")
