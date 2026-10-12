Ito ang simple dating website code gamit lang ang HTML at CSS. I-copy mo ito sa `index.html` at puwede mo nang i-upload sa GitHub.

Writing

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LoveMatch Dating</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background: #ffe6ee;
            text-align: center;
            margin: 0;
        }

        header {
            background: #ff4d79;
            color: white;
            padding: 20px;
        }

        .profile {
            background: white;
            width: 280px;
            margin: 40px auto;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 10px #ccc;
        }

        img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
        }

        button {
            background: #ff4d79;
            color: white;
            border: none;
            padding: 12px 20px;
            margin: 5px;
            border-radius: 20px;
            cursor: pointer;
        }

        button:hover {
            background: #d92758;
        }
    </style>
</head>

<body>

    <header>
        <h1>❤️ LoveMatch</h1>
        <p>Find Someone Special</p>
    </header>

    <div class="profile">
        <img src="https://i.pravatar.cc/300?img=47"
             alt="Sample dating profile">

        <h2>Sophia, 22</h2>
        <p>📍 Manila, Philippines</p>
        <p>I love music, movies, and traveling!</p>

        <button onclick="alert('You passed this profile!')">
            ❌ Pass
        </button>

        <button onclick="alert('You liked this profile! ❤️')">
            ❤️ Like
        </button>
    </div>

    <footer>
        <p>© 2026 LoveMatch Dating</p>
    </footer>

</body>
</html>
