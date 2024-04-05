<!DOCTYPE html>
<html>
<head>
    <title>I LOVE YOU Animation</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-size: 5em;
            font-weight: bold;
            color: red;
            animation: animate 3s linear infinite;
        }

        @keyframes animate {
            0% {
                content: "I LOVE YOU";
            }
            25% {
                content: "I ❤️ YOU";
            }
            50% {
                content: "I ❤️ U";
            }
            75% {
                content: "❤️ U";
            }
            100% {
                content: "❤️";
            }
        }
    </style>
</head>
<body>
</body>
</html>
