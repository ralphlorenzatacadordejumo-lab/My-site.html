# My-site.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Colorful Video Advocacy Campaign</title>

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">

    <style>
        /* General Page Styling */
        body {
            margin: 0;
            padding: 0;
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 99%, #fad0c4 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #333;
        }

        /* Main Card Container */
        .container {
            background-color: rgba(255, 255, 255, 0.95);
            width: 90%;
            max-width: 850px;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            text-align: center;
            margin: 20px;
        }

        /* Header Styling */
        h1 {
            color: #2c3e50;
            margin-bottom: 30px;
            font-size: 2rem;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* Video Wrapper (16:9 Ratio) */
        .video-wrapper {
            position: relative;
            padding-bottom: 56.25%;
            height: 0;
            overflow: hidden;
            border-radius: 15px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.15);
        }

        .video-wrapper iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: none;
        }

        /* Footer Styling */
        footer {
            margin-top: 30px;
            font-size: 0.9rem;
            color: #7f8c8d;
            font-weight: 600;
        }

        /* Button Styling */
        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 24px;
            background-color: #ff6b6b;
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 600;
            transition: transform 0.2s;
        }

        .btn:hover {
            transform: scale(1.05);
        }
    </style>
</head>

<body>
    <div class="container">
        <h1>🎬 Video Advocacy Campaign</h1>

        <div class="video-wrapper">
            <iframe 
                src="https://www.youtube.com/embed/9SaS83GvcDU?rel=0&modestbranding=1&vq=hd1080"
                title="YouTube video player"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen>
            </iframe>
        </div>

        <a href="#" class="btn">Take Action</a>

        <footer>
            Streaming powered by DEJUMO | HD Enabled
        </footer>
    </div>
</body>
</html>
