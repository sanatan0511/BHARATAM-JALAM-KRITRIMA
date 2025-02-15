# BHARATAM-JALAM-KRITRIMA
WATER IS A VITAL THING START WITH WATER &amp; END WITH WATER.&amp; OUT OF 100% ONLY WE GET 1% IS FRESH WATER .THIS WEBSITE DEVOTE TO GROUND WATER.SO STAY TUNED 💦  .WHICH IS OFFICIALLY LAUNCH ON 1ST APRIL 2025:-)





<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Continue Soon</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
            font-family: Arial, sans-serif;
        }
        .message {
            color: silver;
            font-size: 2em;
            margin-bottom: 20px;
        }
        .powered-by {
            color: darkgoldenrod;
            font-size: 1.5em;
            margin-bottom: 20px;
        }
        .timer {
            font-size: 1.2em;
            color: #333;
        }
    </style>
</head>
<body>
    <div class="message">Coming Soon</div>
    <div class="powered-by">Powered & Maintained by Rama Society of Research and Development (RASOR)</div>
    <div class="timer" id="timer"></div>

    <script>
        function countdown() {
            const targetDate = new Date('April 1, 2025 00:00:00').getTime();
            const now = new Date().getTime();
            const distance = targetDate - now;

            const days = Math.floor(distance / (1000 * 60 * 60 * 24));
            const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
            const seconds = Math.floor((distance % (1000 * 60)) / 1000);

            document.getElementById('timer').innerHTML = 
                days + "d " + hours + "h " + minutes + "m " + seconds + "s ";

            if (distance < 0) {
                clearInterval(x);
                document.getElementById('timer').innerHTML = "EXPIRED";
            }
        }

        const x = setInterval(countdown, 1000);
    </script>
</body>
</html>













