<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
            color: #333;
        }
        header {
            background-color: #007acc;
            color: white;
            padding: 1.5rem;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .about-me {
            text-align: center;
        }
        .about-me img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            margin-bottom: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
        }
        .about-me h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        .about-me p {
            font-size: 1.1rem;
            margin-bottom: 15px;
            line-height: 1.6;
        }
        .nav-link {
            text-align: center;
            margin-top: 20px;
        }
        .nav-link button {
            background-color: #007acc;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
        }
        .nav-link button:hover {
            background-color: #005f99;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Personal Page</h1>
    </header>
    <div class="container">
        <section class="about-me">
            <img src="channels4_profile (1).jpg" alt="Profile Picture">
            <h1>Efe Bekteş</h1>
            <p>Hello! I am a computer engineering student at ITU with a strong interest in cryptography and programming.</p>
            <p>I am passionate about learning new technologies and solving challenging problems in the field of computer science.</p>
        </section>
        <section class="nav-link">
            <button onclick="alert('Game link placeholder. Coming soon!')">Go to Word Prediction Game</button>
        </section>
    </div>
</body>
</html>
