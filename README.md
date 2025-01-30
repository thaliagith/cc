<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>PlayBoyCari's Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        h1 {
            color: rgb(35, 155, 55);
            text-align: center;
            margin-top: 20px;
        }

        ol {
            list-style-type: decimal;
            margin-left: 20px;
            padding-left: 20px;
        }

        p {
            color: red;
            text-align: center;
            font-weight: bold;
        }

        img {
            display: block;
            margin: 20px auto;
            width: 70px;
            height: 90px;
        }

        /* Ensures the page looks good on mobile */
        @media (max-width: 600px) {
            h1 {
                font-size: 1.5em;
            }
            ol {
                font-size: 14px;
            }
        }
    </style>
</head>
<body>
    <h1>PlayBoyCari Was Here</h1>
    
    <ol>
        <li>EarFQuake</li>
        <li>Magnolia</li>
    </ol>
    
    <ol>
        <li>Bartier Cardi</li>
        <li>Carnival</li>
    </ol>

    <ol>
        <li>Off The Grid</li>
        <li>Fe!N</li>
    </ol>

    <ol>
        <li>Greatest</li>
        <li>XXL Freshmen Cypher</li>
    </ol>

    <p>We love Carti.</p>

    <ol>
        <li>Timeless</li>
        <li>Raf</li>
    </ol>

    <ol>
        <!-- Image Added Here -->
        <img id="cartiImage" alt="Playboi Carti Image">
        <li>Wokeuplikethis</li>
        <li>Shoota</li>
    </ol>

    <!-- Random Image Script -->
    <script>
        // Array of image paths (change to the actual file paths of your images)
        const images = [
            'carti_1.jpg', // Image 1
            'carti_2.jpg', // Image 2
            'carti_3.jpg', // Image 3
            'carti_4.jpg', // Image 4
            'carti_5.jpg'  // Image 5
        ];

        // Randomly select an image from the array
        const randomImage = images[Math.floor(Math.random() * images.length)];

        // Set the source of the image element
        document.getElementById('cartiImage').src = randomImage;
    </script>

</body>
</html>
