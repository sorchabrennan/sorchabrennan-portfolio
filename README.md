<!-- Personal Portfolio Website -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/css/bootstrap.min.css">
    <link rel="stylesheet" href="css/styles.css">
    <style>
        body {
            background-color: #f3f4f6;
            font-family: Arial, sans-serif;
        }
        h1, h2 {
            color: #1f2937;
        }
        .section-box {
            background-color: white;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .section-box:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
        }
        .more-about-me-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .more-about-me-card {
            flex: 1 1 calc(45% - 20px);
            max-width: 500px;
        }
    </style>
</head>
<body>
    <div class="container mt-5">
        <section id="about-me" class="mb-5">
            <div class="section-box">
                <h1>About Me</h1>
                <p>Hello! My name is Sorcha Brennan, I am a first year student studying Interaction Design at the University of Limerick.</p>
                <p>I chose this course because i wanted to combine both technical and creative skills.</p>
                <p><b>Areas of interest:</b> Product Design, Graphic Design,videography and photography .</p>
                <p><b>Career Ambitions:</b> Develop my UI/UX design skills and work in a role that I am passionate about.</p>
            </div>
        </section>

        <section id="skills-interests" class="mb-5">
            <div class="p-4 rounded" style="background-color: #d9edf7;">
                <h2>Skills & Interests</h2>
                <table class="table table-bordered">
                    <thead>
                        <tr>
                            <th>Skill</th>
                            <th>Proficiency</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>HTML</td>
                            <td>Learning </td>
                        </tr>
                        <tr>
                            <td>Product Design</td>
                            <td>Beginner</td>
                        </tr>
                        <tr>
                            <td>Graphic Design</td>
                            <td>Beginner</td>
                        </tr>
                        <tr>
                           <td>Photography/Videography</td>
                           <td>Beginner</td>
                    </tbody>
                </table>
            </div>
        </section>

        <section id="more-about-me" class="mb-5">
        <div class="p-4 rounded" style="background-color: #dff0d8;">
            <div class="section-box mb-4">
                <h2>More About Me</h2>
            </div>
            <div class="more-about-me-container">
                <div class="section-box more-about-me-card">
                    <h2>Future Goals</h2>
                    <p>Complete my degree and gain practical experience to improve my skills which will allow me to secure a full time job as a designer.  </p>
                </div>
                <div class="section-box more-about-me-card">
                    <h2>Inspirations</h2>
                    <p>Dieter Rams </p>
                    <p>James Dyson</p>
                    <p>Jony Ive</p>
                    <p>Vivenne Westwood</p>
                </div>
                <div class="section-box more-about-me-card">
                    <h2>Hobbies & Passions</h2>
                    <p>I enjoy excercising and sketching which help me to develop discipline, patience and creativity which are all neccessary skills.</p>
                </div>
                <div class="section-box more-about-me-card">
                    <h2>My Favorite Projects</h2>
                    <p>Designing a water vessel which holds one litre of water.</p>
                    <p>Redesigning an album cover for a vinyl record.</p>
                </div>
            </div>
        </section>

        <section id="reflection" class="mb-5">
            <div class="section-box"style="background-color: #D8BFD8;">
                <h2>Reflection & Future Plans</h2>
                <p>This page currently represents my current skills and interests.</p>
                <p>In the future, I would like to add images or links to images of some of my projects done .</p>
            </div>
        </section>

        <section id="design-process" class="mb-5">
            <div class="section-box"style="background-color: #F5B78E;">
                <h2>My Design Process</h2>
                <p>Below is the scanned image of my boxified design layout.</p>
                <img src="images/IMG_8459.jpg" alt="Boxified Design Layout" class="img-fluid">
            </div>
        </section>
    </div>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
</body>
</html>
