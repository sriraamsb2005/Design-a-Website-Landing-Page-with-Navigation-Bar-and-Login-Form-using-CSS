# Design-a-Website-Landing-Page-with-Navigation-Bar-and-Login-Form-using-CSS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Water Board Management System</title>
    <link rel="stylesheet" href="water.css">
</head>
<body>
    <nav class="navbar">
        <img src="logo.jpeg" alt="Water Board Logo" class="logo">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
            <li><a href="#">About</a></li>
        </ul>
    </nav>
    <section class="landing">
        <h1>Welcome to Water Board Management System</h1>
        <p>Manage your water supply services efficiently and securely.</p>
    </section>
    <section class="login-section">
        <form class="login-form">
            <h2>Login</h2>
            <label for="username">Username</label>
            <input type="text" id="username" name="username" required>

            <label for="password">Password</label>
            <input type="password" id="password" name="password" required>

            <button type="submit">Login</button>
        </form>
    </section>

</body>
</html>
--------------------------------------(html)-----------------------------------------

/* General */
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
}

/* Navbar */
.navbar {
    display: flex;
    align-items: center;
    background-color: #004080;
    padding: 10px 20px;
    justify-content: space-between;
}

.navbar .logo {
    height: 50px;
}

.navbar ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

.navbar li {
    margin: 0 15px;
}

.navbar a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

.navbar a:hover {
    color: #ffcc00;
}

/* Landing Section with Background */
.landing {
    text-align: center;
    padding: 100px 20px;
    color: white;
    background-image: url('logo1.jpeg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}

.landing h1 {
    font-size: 32px;
    background-color: rgba(0, 64, 128, 0.6);
    display: inline-block;
    padding: 10px 20px;
    border-radius: 10px;
}

.landing p {
    font-size: 18px;
    margin-top: 20px;
    background-color: rgba(255, 255, 255, 0.7);
    color: #000;
    display: inline-block;
    padding: 8px 16px;
    border-radius: 10px;
}

/* Login Section */
.login-section {
    display: flex;
    justify-content: center;
    padding: 40px 0;
    background-color: #ffffff;
}

.login-form {
    background-color: #f9f9f9;
    padding: 30px;
    border-radius: 10px;
    width: 300px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.login-form h2 {
    text-align: center;
    color: #004080;
}

.login-form label {
    display: block;
    margin-top: 15px;
    margin-bottom: 5px;
    font-weight: bold;
}

.login-form input {
    width: 100%;
    padding: 8px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.login-form button {
    width: 100%;
    padding: 10px;
    background-color: #004080;
    color: white;
    border: none;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
}

.login-form button:hover {
    background-color: #0059b3;
}
-----------------------------------------------( css)----------------------------------------------------------
