# TeleBee
> The project for MERN course.

<h2 id="table-of-contents"> Table of Contents</h2>
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#problemStatement">Problem Statement</a></li>
    <li><a href="#motivation">Motivation</a></li>
    <li><a href="#utility">Utility Diagram</a></li>
    <li><a href="#folderstructure">Folder structure</a></li>
    <li><a href="#structuralinfo">Structural Information</a></li>
    <li><a href="#techno">Technology</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#output">Output</a></li>
    <li><a href="#setup">Setup</a> <ul>
        <li><a href="#">API</a></li>
        <li><a href="#">Admin</a></li>
        <li><a href="#">Client</a></li>
       </ul></li>
    <li><a href="#fs">Future Scope</li>
  
  </ol>
</details>

<br>

<h4>Presentation slides: <a href="https://docs.google.com/presentation/d/1as_8of5OwUAOXIbNjGvh98p33Cw_oXA_/edit?usp=sharing&ouid=101603160054612643101&rtpof=true&sd=true"> here </a> </h4>

<br>
<h1 id="problemStatement">Problem Statement</h1>
<p>Implementating Online Streaming Platform(OTT) with the help of MERN stacK technology</p>

<h1 id="motivation">Motivation</h1>
<p>Today, people prefer to stay home and do things they love. One such thing our entire team enjoys is binge-watching series and watching movies. Acknowledging the existence of our fellow binge-watchers, we decided to build an OTT platform for all, to give them access to all their favorite shows, series, and movies of various genres. 
</p>

<h1 id="utility">Utility Diagrams</h1>
<h1>Use Case Diagram</h1>
<p>
  
  <img src="https://cdn.discordapp.com/attachments/819850728427225108/1046519438180106280/WhatsApp_Image_2022-11-24_at_11.33.41_AM.jpeg" width="350" alt="accessibility text">
</p>
<br>
<h1>Activity Diagram</h1>
<p>
  REGISTER <br>
  <img src="https://cdn.discordapp.com/attachments/819850728427225108/1046519655713472542/WhatsApp_Image_2022-11-24_at_11.35.07_AM.jpeg" width="350" alt="accessibility text">
</p>
<br>
<p>
WATCH <br>
  <img src="https://cdn.discordapp.com/attachments/819850728427225108/1046519837926621274/WhatsApp_Image_2022-11-24_at_11.36.10_AM.jpeg" width="350" alt="accessibility text">
</p>



<h1 id="folderstructure">Folder structure</h1>
   
    ├── Admin
    │   ├── nodemodules
    |    |── public
    |        |── index.html
    |    |── src
    │       ├── components
    │       ├── context
    │       ├── pages
    │       ├── app.jsx
    │       ├── App.jsx
    │       ├── dummyData.jsx
    |       │── firebase.jsx
    |       |── index.jsx   
    ├── api
    |    ├── nodemodules
    |    |── models
    |        |── List.jsx
    |        |── Movie.jsx
    |        |── User.jsx
    |   |── routes
    │       ├── auth.jsx
    │       ├── movies.jsx
    │       ├── lists.jsx
    │       ├── users.jsx
    |    |──index.jsx
    |    |──verifytoken.jsx
    |
    │   
    ├── client
    |    ├── nodemodules
    |    |── models
    |        |── List.jsx
    |        |── Movie.jsx
    |        |── User.jsx
    |   |── src
    │       ├── authContext.jsx
    |            |── apiCalls.jsx
    |            |── AuthActions.jsx
    |            |── AuthContext.jsx
    |            |── AuthReducer.jsx
    │       ├── components
    |            |── featured
    |            |── list
    |            |── listitem
    |            |── navbar
    │       ├── pages
    |            |── home
    |            |── login
    |            |── register
    |            |── watch
    │       ├── App.jsx
    |    |──index.jsx
    |    |──verifytoken.jsx
     
    
<h1 id="structuralinfo">Structural Information</h1>
<h3><strong>Server</strong></h3>
<p>Contains an API , created by Node.js, Express and MongoDB. Using RESTful APIs.</p>

<h3><strong>Client</strong></h3>
<p>The client for user, built with React, and Material UI</p>

<h3><strong>Admin</strong></h3>
<p>The management admin page, created with React, and Material UI
</p>
<br>

<h1 id="techno">Technology</h1>
<ul>
  <li>MongoDb</li>
  <li>Express JS</li>
  <li>React JS</li>
  <li>Node JS</li>
</ul>

<h3>- Server</h3>

| Plugin | README |
| ------ | ------ |
| bcryptjs | [plugins/bcryptjs/README.md](https://github.com/dcodeIO/bcrypt.js/blob/master/README.md) |
| express | [plugins/express/README.md](https://github.com/expressjs/express/blob/master/Readme.md) |
| jsonwebtoken | [plugins/jsonwebtoken/README.md](https://github.com/auth0/node-jsonwebtoken/blob/master/README.md) |
| mongoose | [plugins/mongoose/README.md](https://github.com/Automattic/mongoose/blob/master/README.md) |
| nodemon | [plugins/nodemon/README.md](https://github.com/remy/nodemon/blob/master/README.md) |
| cloudinary | [plugins/cloudinary/README.md](https://github.com/cloudinary) |

<br>

### - Admin 

| Plugin | README |
| ------ | ------ |
| axios | [plugins/axios/README.md](https://github.com/axios/axios/blob/master/README.md) |
| material-ui | [plugins/material-ui/README.md](https://github.com/mui-org/material-ui/blob/next/README.md) |
| react | [plugins/react/README.md](https://github.com/facebook/react/blob/master/README.md) |
| react-router-dom | [plugins/react-router/README.md](https://github.com/ReactTraining/react-router/blob/master/README.md) |
| recharts | [plugins/recharts/README.md](https://github.com/recharts/recharts/blob/master/README.md) |

<br>

### - Client

| Plugin | README |
| ------ | ------ |
| axios | [plugins/axios/README.md](https://github.com/axios/axios/blob/master/README.md) |
| react | [plugins/react/README.md](https://github.com/facebook/react/blob/master/README.md) |
| react-router-dom | [plugins/react-router/README.md](https://github.com/ReactTraining/react-router/blob/master/README.md) |
| sass | [plugins/sass/README.md](https://github.com/sass/sass/blob/main/README.md) |

<br>
<h1 id="features">Features</h1>
User

Register-Login-Logout

Login-Update-Delete-Statis-Logoutaccount

Movie

Watch
Download-pictureInPicture-PlaybackSpeed-random-filter type of movies/series
Create-update-delete-random movie

List
Watch filter-filter genre of list
Create-update-delete-random list





<h1 id="output">Output</h1>

  <img src="https://cdn.discordapp.com/attachments/828162861557088276/1046651949665226752/image.png" alt="accessibility text">

  <img src="https://cdn.discordapp.com/attachments/828162861557088276/1046652024709713980/image.png" alt="accessibility text">

If wrong id entered
<img src="https://cdn.discordapp.com/attachments/828162861557088276/1046661129356722238/image.png" alt="accessibility text">

 <img src="https://cdn.discordapp.com/attachments/828162861557088276/1046661173560479765/unknown.png" alt="accessibility text">

  <img src="https://cdn.discordapp.com/attachments/828162861557088276/1046663741325979688/unknown.png" alt="accessibility text">


<br>
ADMIN

LOGIN DETAILS => ID = abc & Password = 12345678
 <img src="https://cdn.discordapp.com/attachments/828162861557088276/1046661208834588723/unknown.png" alt="accessibility text">
 <img src="https://cdn.discordapp.com/attachments/828162861557088276/1046661302854107226/unknown.png" alt="accessibility text">
 <img src="https://cdn.discordapp.com/attachments/828162861557088276/1046661434504925194/unknown.png" alt="accessibility text">


<h1 id="setup">Setup</h1>

API <br>
npm install
<br>
create an .env file  => 
<br>
MONGO_URL = YOUR_MONGO_URL
<br>
SECRET_KEY = YOUR_SECRET_KET
<br>
npm start


CLIENT 
<br>
npm install 
<br>
npm start
<br> <br>
ADMIN
<br>
npm install <br>
create an .env file  => PORT = PORT_OF_YOUR_CHOICE
<br>
npm start



<h1 id="fs">Future Scope</h1>

1) To Replace axios with our custom library
2) To Implement a payment portal
3) Last Watched and Continue Watching
4)  To Implement a recommendation system


