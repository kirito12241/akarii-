<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Message</title>
    <style>
        /* Add your custom CSS styles here */
        body {
            background-color: #000;
            text-align: center;
            color: #fff;
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body>
    <h1>Click the button to see a message and GIF!</h1>
    <button id="showMessage">Click me!</button>
    <div id="messageContainer" style="display: none;">
        <p>I miss you</p>
        <img src="iloveyou.gif" alt="I love you GIF" width="200">
    </div>
    <script>
        const showMessageButton = document.getElementById('showMessage');
        const messageContainer = document.getElementById('messageContainer');
        
        showMessageButton.addEventListener('click', () => {
            messageContainer.style.display = 'block';
        });
    </script>
</body>
</html>
