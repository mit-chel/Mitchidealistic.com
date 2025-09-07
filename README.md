<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My First Webpage</title>
  
  <!-- CSS styling -->
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #4CAF50;
      color: white;
      padding: 15px;
      text-align: center;
    }
    nav {
      background: #333;
      padding: 10px;
    }
    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      padding: 20px;
    }
    footer {
      text-align: center;
      background: #333;
      color: white;
      padding: 10px;
      position: fixed;
      width: 100%;
      bottom: 0;
    }
    button {
      padding: 10px 20px;
      margin-top: 20px;
      background: #4CAF50;
      color: white;
      border: none;
      cursor: pointer;
      border-radius: 5px;
    }
    button:hover {
      background: #45a049;
    }
  </style>
</head>
<body>

  <!-- Page Header -->
  <header>
    <h1>Welcome to My Webpage</h1>
  </header>

  <!-- Navigation Menu -->
  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>

  <!-- Main Content -->
  <main>
    <h2>Hello, World!</h2>
    <p>This is a simple webpage built with HTML, CSS, and JavaScript.</p>
    <button onclick="sayHello()">Click Me</button>
  </main>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 My Website</p>
  </footer>

  <!-- JavaScript -->
  <script>
    function sayHello() {
      alert("Hello! Thanks for clicking 😊");
    }
  </script>

</body>
</html>
