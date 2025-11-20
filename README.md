# git-fetch

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample HTML Page</title>
    <style>
        /* Basic CSS styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #007BFF;
            color: white;
            padding: 15px 0;
        }
        button {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 10px 20px;
            margin-top: 20px;
            cursor: pointer;
            font-size: 16px;
            border-radius: 5px;
        }
        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My HTML Page</h1>
    </header>

    <main>
        <p>This is a simple HTML page with CSS styling and JavaScript functionality.</p>
        <button onclick="showMessage()">Click Me</button>
        <p id="output"></p>
    </main>

    <script>
        // JavaScript function to display a message
        function showMessage() {
            document.getElementById("output").textContent = "Hello! You clicked the button.";
        }
    </script>

</body>
</html>
