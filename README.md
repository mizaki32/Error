
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be My Valentine?</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            text-align: center;
            background-image: url('your-image.jpg'); /* Replace with your image file name */
            background-size: cover;
            background-position: center;
            color: white; /* Change text color for better visibility */
        }
        .container {
            background-color: rgba(255, 255, 255, 0.8); /* Semi-transparent background */
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #ff4081;
            font-size: 2.5em;
        }
        p {
            font-size: 1.2em;
            color: #333;
        }
        .button {
            display: inline-block;
            margin: 10px;
            padding: 10px 25px;
            background-color: #ff4081;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .button:hover {
            background-color: #e91e63;
        }
        .response {
            margin-top: 20px;
            font-size: 1.5em;
            color: #333;
        }
    </style>
    <script>
        function showResponse(answer) {
            const responseDiv = document.getElementById('response');
            if (answer === 'yes') {
                responseDiv.innerText = 'Syempre naman sayang 2yrs no😜';
            } else {
                responseDiv.innerText = 'Wala ka magagawa bf mo ako😜';
            }
        }
    </script>
</head>
<body>

<div class="container">
    <h1>Will You Be My Valentine?</h1>
    <p>Taby  Will you be my Valentine?</p>
    <button class="button" onclick="showResponse('yes')">Yes💖</button>
    <button class="button" onclick="showResponse('no')">No😢</button>
    <div class="response" id="response"></div>
</div>

</body>
</html>
