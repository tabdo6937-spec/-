<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abdel Nasser T - Programming Courses and Resources</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        nav {
            background-color: #ddd;
            padding: 10px;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
        }
        .main-content {
            padding: 20px;
            text-align: center;
        }
        .login-form {
            margin: 20px auto;
            width: 300px;
            padding: 20px;
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .login-form input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            box-sizing: border-box;
        }
        .login-form button {
            width: 100%;
            padding: 10px;
            background-color: #333;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .mascot {
            margin: 20px 0;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Abdel Nasser T</h1>
        <p>Your go-to site for programming courses, templates, and images!</p>
    </header>
    
    <nav>
        <a href="#courses">Courses</a>
        <a href="#templates">Templates</a>
        <a href="#images">Images</a>
        <a href="#contact">Contact</a>
    </nav>
    
    <div class="main-content">
        <h2>Welcome to Abdel Nasser T</h2>
        <p>Explore professional programming templates, high-quality images, and comprehensive courses to level up your skills.</p>
        
        <!-- Mascot: A face with a computer and hacker image -->
        <div class="mascot">
            <img src="https://via.placeholder.com/200?text=Computer+Hacker+Face" alt="A stylized face with a computer and hacker elements" width="200">
            <p>Meet our mascot: The ultimate programmer hacker!</p>
        </div>
        
        <!-- Login Form -->
        <div class="login-form">
            <h3>Log In</h3>
            <form action="/login" method="POST">  <!-- In a real app, this would point to a backend endpoint -->
                <label for="username">Username:</label>
                <input type="text" id="username" name="username" required>
                
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>
                
                <button type="submit">Log In</button>
            </form>
            <p>Don't have an account? <a href="#register">Register here</a>.</p>
        </div>
    </div>
    
    <footer>
        <p>Contact us: Phone: 01098181296 | Location: Assiut Governorate, Egypt</p>
        <p>&copy; 2023 Abdel Nasser T. All rights reserved.</p>
    </footer>
</body>
</html>
 
