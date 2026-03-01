/* GENERAL */
body {
    margin: 0;
    background: #0a0a0a;
    font-family: Arial, sans-serif;
    color: white;
    text-align: center;
}

/* NAVBAR */
nav {
    background: #111;
    padding: 15px;
    box-shadow: 0 0 15px #00ffaa50;
}

nav a {
    margin: 0 15px;
    color: #00ffcc;
    text-decoration: none;
    font-weight: bold;
    font-size: 18px;
    transition: 0.3s;
}

nav a:hover {
    color: #00bfa5;
    text-shadow: 0 0 10px #00ffcc;
}

/* HEADER */
header {
    padding: 60px 20px;
}

header h1 {
    font-size: 50px;
    text-shadow: 0 0 15px #00ffcc;
    color: #00ffcc;
}

header p {
    font-size: 20px;
    color: #ccc;
}

/* CONTENT BOXES */
.section {
    padding: 40px 20px;
    max-width: 900px;
    margin: auto;
}

.box {
    background: #111;
    border-radius: 10px;
    padding: 30px;
    margin-bottom: 20px;
    box-shadow: 0 0 20px #00ffcc30;
}

.box h2 {
    color: #00ffcc;
    text-shadow: 0 0 10px #00ffcc;
}

.box p {
    color: #ccc;
    font-size: 17px;
    line-height: 1.6;
}

/* FOOTER */
footer {
    padding: 20px;
    margin-top: 40px;
    background: #111;
    color: #777;
    font-size: 14px;
}
<!DOCTYPE html>
<html>
<head>
    <title>The Hive — Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<nav>
    <a href="index.html">Home</a>
    <a href="dxrp.html">DXRP</a>
    <a href="members.html">Members</a>
    <a href="rules.html">Rules</a>
</nav>

<header>
    <h1>THE HIVE</h1>
    <p>We rise together. We fight together. We never fall.</p>
</header>

<div class="section">
    <div class="box">
        <h2>Welcome to The Hive</h2>
        <p>A dark, united faction built on loyalty, power, and teamwork.</p>
    </div>

    <div class="box">
        <h2>DXRP Dominance</h2>
        <p>We control, defend, and dominate together. The Hive moves as one mind.</p>
    </div>

    <div class="box">
        <h2>Join the Swarm</h2>
        <p>Earn your place. Respect the Hive. Protect the Hive.</p>
    </div>
</div>

<footer>© 2026 The Hive</footer>

</body>
</html>
