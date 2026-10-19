# index.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EduWorld - Learning Platform</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h2>📚 EduWorld</h2>

        <nav>
            <a href="#home">Home</a>
            <a href="#courses">Courses</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero" id="home">
        <div>
            <h1>Your Learning <br> Journey Starts Here</h1>
            <p>Access courses, resources and guidelines<br>
            to achieve your goals.</p>
            <button type="button">Get Started</button>
        </div>
    </section>

    <section class="courses" id="courses">

        <div>
            <h3>💻 Web Technologies</h3>
            <p>Learn HTML, CSS and JavaScript.</p>
        </div>

        <div>
            <h3>🗄️ Database Systems</h3>
            <p>Work with real-world databases.</p>
        </div>

        <div>
            <h3>🐍 Python Programming</h3>
            <p>Learn programming from basics.</p>
        </div>

    </section>

    <section class="quote">
        <h2>Small steps every day lead to big results.</h2>
    </section>

    <section class="bottom" id="about">

        <div>
            <h3>Registration Form</h3>

            <form id="registrationForm">

                <label for="name">Full Name:</label>
                <input type="text" id="name" name="name"
                       placeholder="Enter your name" required>
                <br><br>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email"
                       placeholder="Enter your email" required>
                <br><br>

                <label for="password">Password:</label>
                <input type="password" id="password" name="password"
                       placeholder="Enter password" required>
                <br><br>

                <label>Gender:</label>
                <input type="radio" name="gender" value="Male"> Male
                <input type="radio" name="gender" value="Female"> Female
                <br><br>

                <label for="department">Department:</label>
                <select id="department" name="department" required>
                    <option value="">Select Department</option>
                    <option value="CS">Computer Science</option>
                    <option value="SE">Software Engineering</option>
                    <option value="IT">Information Technology</option>
                </select>
                <br><br>

                <label>Courses:</label><br>
                <input type="checkbox" name="courses" value="Web Technologies">
                Web Technologies<br>

                <input type="checkbox" name="courses" value="Database Systems">
                Database Systems<br>

                <input type="checkbox" name="courses" value="Programming">
                Programming
                <br><br>

                <label for="message">Message:</label><br>
                <textarea id="message" name="message"
                          placeholder="Write your message here..."
                          rows="4" cols="30"></textarea>
                <br><br>

                <button type="submit">Register</button>
                <button type="reset">Reset</button>

            </form>
        </div>

        <div id="contact">
            <h3>Listen to Our Message</h3>

            <audio controls>
                <source src="message.mp3" type="audio/mpeg">
                Your browser does not support audio.
            </audio>

            <br><br>

            <img src="campus.jpg"
                 alt="University campus" width="200">

            <p>Welcome to EduWorld!</p>
            <p>Learn new skills and build your future with us.</p>
        </div>

    </section>

    <footer>
        <p>© 2026 EduWorld. All rights reserved.</p>
    </footer>

</body>
</html>