<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tayaba Tariq Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        /* General Styling */
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background: #f4f4f4;
        }

        h2, h3 {
            color: #333;
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }

        div {
            margin-bottom: 20px;
        }

        ul {
            list-style: square;
            padding-left: 20px;
        }

        li {
            margin: 5px 0;
        }

        p {
            color: #555;
        }

        /* Animation Styling */
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .animated {
            animation: fadeIn 1s ease-in-out;
        }

        /* Image Styling */
        .header-image {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }

        .cta {
            text-align: center;
            padding: 15px;
            background: #0078ff;
            color: white;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            display: inline-block;
            margin-top: 20px;
        }

        .cta:hover {
            background: #0056c7;
        }
    </style>
</head>
<body>
    <div class="container">
        <div align="center" class="animated">
            <img src="https://via.placeholder.com/800x400?text=Welcome+to+My+Portfolio" alt="Portfolio Header" class="header-image">
            <h3>I am Tayaba Tariq, a passionate and skilled front-end developer specializing in creating visually stunning, responsive, and user-friendly websites.</h3>
            <p>
                With hands-on experience in modern web technologies like HTML, CSS, JavaScript, GSAP, and ScrollTrigger, I thrive on turning creative ideas into reality. 
                As a BSCS student at Virtual University, I am committed to lifelong learning, currently mastering React with plans to advance into Redux. 
                My work reflects my dedication to innovation, quality, and collaboration.
            </p>
        </div>

        <div class="animated">
            <h2>Skills and Expertise</h2>
            <ul>
                <li>Proficient in HTML, CSS, JavaScript, Tailwind CSS, and Bootstrap.</li>
                <li>Experience with animation libraries like GSAP and ScrollTrigger.</li>
                <li>Programming knowledge in C++ and C.</li>
                <li>Exploring advanced frameworks like React to build scalable web applications.</li>
                <li>Eager to embrace new tools and techniques to enhance user experiences.</li>
            </ul>
        </div>

        <div class="animated">
            <h2>Passion for Learning</h2>
            <p>
                I believe that growth is a continuous journey. Over the past year, I have immersed myself in web development, successfully completing certifications in JavaScript, web design, and HTML. 
                My learning path includes practical internships where I applied my skills to real-world projects, gaining valuable experience. 
                I am now on a journey to learn React and Redux, expanding my ability to create robust, feature-rich web applications.
            </p>
        </div>

        <div class="animated">
            <h2>Career Goals</h2>
            <p>
                My ultimate goal is to be a leader in front-end development, contributing to impactful projects that prioritize user experience and functionality. 
                By mastering tools like React and Redux, I plan to push the boundaries of what's possible in web development. 
                I am eager to collaborate with like-minded professionals and explore new opportunities to grow and make a difference.
            </p>
        </div>

        <div class="animated">
            <h2>Call to Action</h2>
            <p>
                Feel free to connect with me to explore exciting opportunities or discuss potential collaborations. 
                I am always eager to contribute to projects that inspire creativity and innovation.
            </p>
            <a href="mailto:tayaba@example.com" class="cta">Get in Touch</a>
        </div>
    </div>
</body>
</html>
