# maximum160.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A Little Break for Leslie</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to bottom, #d4f1d4, #a3d9ff);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            color: #333;
        }
        .container {
            text-align: center;
            background: rgba(255, 255, 255, 0.9);
            padding: 20px 40px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            max-width: 500px;
        }
        h1 {
            font-size: 28px;
            color: #2e7d32;
        }
        p {
            font-size: 18px;
            line-height: 1.5;
        }
        .buttons {
            margin: 20px 0;
        }
        button {
            padding: 10px 20px;
            margin: 10px;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
            transition: background 0.3s;
        }
        #yes-btn {
            background: #4caf50;
            color: white;
        }
        #yes-btn:hover {
            background: #388e3c;
        }
        #maybe-btn {
            background: #ffca28;
            color: #333;
        }
        #maybe-btn:hover {
            background: #ffb300;
        }
        #response {
            margin-top: 20px;
            font-size: 16px;
            color: #d81b60;
        }
        footer {
            margin-top: 20px;
            font-size: 14px;
            color: #555;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hey Leslie!</h1>
        <p>I know you're super busy with finals, so I made this little page to brighten your day! 😊</p>
        <p>We talked about grabbing snacks and walking by the Waterfront or a park. When you get a break, would you be up for a chill hangout on Saturday or Sunday?</p>
        <div class="buttons">
            <button id="yes-btn" onclick="showResponse('yes')">Yes, sounds fun!</button>
            <button id="maybe-btn" onclick="showResponse('maybe')">Maybe later, finals are crazy!</button>
        </div>
        <div id="response"></div>
        <footer>Good luck crushing those exams! — [Your Name]</footer>
    </div>

    <script>
        function showResponse(choice) {
            const responseDiv = document.getElementById('response');
            if (choice === 'yes') {
                responseDiv.innerHTML = 'Awesome! I’ll text you to confirm Saturday or Sunday. 😄';
            } else {
                responseDiv.innerHTML = 'No worries at all, focus on those finals! Let me know when you’re free. 🍀';
            }
        }
    </script>
</body>
</html>
