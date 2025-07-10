<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Your GitHub Page</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    .navbar {
      display: flex;
      position: fixed;
      top: 0;
      left: 0;
      background-color: #333;
      padding: 10px;
      z-index: 1000;
    }

    .dropdown {
      position: relative;
      margin-right: 20px;
    }

    .dropbtn {
      background-color: #333;
      color: white;
      padding: 10px;
      font-size: 16px;
      border: none;
      cursor: pointer;
    }

    .dropbtn:hover {
      background-color: #555;
    }

    .dropdown-content {
      display: none;
      position: absolute;
      background-color: #f9f9f9;
      min-width: 160px;
      top: 40px;
      left: 0;
      box-shadow: 0px 8px 16px rgba(0,0,0,0.2);
      z-index: 1;
    }

    .dropdown-content a {
      color: black;
      padding: 10px 16px;
      text-decoration: none;
      display: block;
    }

    .dropdown-content a:hover {
      background-color: #ddd;
    }

    .dropdown:hover .dropdown-content {
      display: block;
    }

    .content {
      padding: 80px 20px;
    }
  </style>
</head>
<body>
  <div class="navbar">
    <div class="dropdown">
      <button class="dropbtn">Cooking</button>
      <div class="dropdown-content">
        <a href="#">Recipes</a>
        <a href="#">Tips</a>
        <a href="#">Favorites</a>
      </div>
    </div>
    <div class="dropdown">
      <button class="dropbtn">About</button>
      <div class="dropdown-content">
        <a href="#">Story</a>
        <a href="#">Contact</a>
      </div>
    </div>
  </div>

  <div class="content">
    <h1>Welcome to Your Page</h1>
    <p>Put your awesome Cooking and About content right here.</p>
  </div>
</body>
</html>
