<html>
  <head>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/modernizr/2.8.3/modernizr.js"></script>
  </head>
  <body>

    <script src="loads.js"></script>
    <div class="se-pre-con"></div>
    <style>
      #example {
        top: 50%;
        left: 50%;
        width: 30em;
        height: 18em;
        margin-top: -9em;
        margin-left: -15em;
        border: 1px solid RGBA;
        background-color:RGBA;
        position: fixed;
      }
    </style>
  </head>
  <body>
    <div id="example"><center>
      <form>
        <label for="email">Email</label>
        <input type="email" id="email" />
        <br>
        <label for="password">Password</label>
        <input type="password" id="password" />
        <br>
        <button id="signup-btn">Sign Up</button onclick = popup>
        <button id="logout-btn">Logout</button>
      </form>
    </center></div>
    
    <script src="https://www.gstatic.com/firebasejs/8.1.1/firebase-app.js"></script>
    <!-- Below is the additional script for Firebase Auth -->
    <script src="https://www.gstatic.com/firebasejs/8.1.1/firebase-auth.js"></script>

    <script>
      var firebaseConfig = {
        apiKey: "AIzaSyAl_-mSzachIEJshqgKXqtQY2_6ZhFSv90",
        authDomain: "esp32-weather-app.firebaseapp.com",
        databaseURL: "https://esp32-weather-app-default-rtdb.europe-west1.firebasedatabase.app",
        projectId: "esp32-weather-app",
        storageBucket: "esp32-weather-app.appspot.com",
        messagingSenderId: "315549292153",
        appId: "1:315549292153:web:f955c74aee52d61546a6a8",
      };
      firebase.initializeApp(firebaseConfig);

      const auth = firebase.auth();
    </script>

    <script src="scripts/script.js"></script>
    <link rel="stylesheet" href="style3.css">
    
    
  </body>
</html>
