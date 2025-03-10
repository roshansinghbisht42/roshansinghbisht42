<!DOCTYPE html>
<html lang="en">
<head>

    <title>Km Seema</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background: url('https://static.vecteezy.com/system/resources/thumbnails/022/575/456/small_2x/chamomile-flower-field-camomile-in-the-nature-field-of-camomiles-at-sunny-day-at-nature-camomile-daisy-flowers-in-summer-day-chamomile-flowers-field-wide-background-in-sun-light-generative-ai-photo.jpg') no-repeat center center/cover;
            color: white;
        }
        header {
            background-color: rgba(51, 51, 51, 0.8);
            color: white;
            padding: 20px;
            font-size: 24px;
            transition: transform 0.3s ease-in-out;
        }
        header:hover {
            transform: scale(1.1);
            color: yellowgreen;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            background: rgba(0, 0, 0, 0.7);
            padding: 20px;
            border-radius: 10px;
        }
        h2 {
            transition: transform 0.3s ease-in-out, color 0.3s ease-in-out;
        }
        h2:hover {
            transform: scale(1.1);
            color: lightblue;
        }
        .gallery {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .gallery img, .gallery video {
            width: 100%;
            max-width: 600px;
            margin: 15px 0;
            border-radius: 10px;
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
            backdrop-filter: blur(10px);
            background: rgba(255, 255, 255, 0.2);
            padding: 10px;
            border-radius: 20px;
            box-shadow: 0 4px 6px rgba(255, 255, 255, 0.2);
        }
        .gallery img:hover, .gallery video:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 12px rgba(255, 255, 255, 0.4);
        }
        footer {
            background-color: rgba(51, 51, 51, 0.8);
            color: white;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
         Km Seema Website
    </header>
    <div class="container">
        <h2>Birthday Gift from me..</h2>
        <p>A simple website that shows some images and video</p>
        <h2>Gallery</h2>
        <div class="gallery">
            <img src="pic1.jpg" alt="Image 1">
            <img src="pic2.jpg" alt="Image 2">
            <img src="pic3.jpg" alt="Image 3">
            <img src="pic4.jpg" alt="Image 4">
        </div>
        <h2>Video Section</h2>
        <div class="gallery">
            <video controls>
                <source src="video1.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </div>
    </div>
    <footer>
        &copy; 2025 Km Seema Website. All rights reserved.
    </footer>
</body>
</html>
