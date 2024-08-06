<html>
<head>
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css"> 
</head>
<body>
    <section id="about">
        <h2 class="centered-heading">About</h2> 
        <img src="images/about.jpg" alt="Your Name" class="profile-image">
        <div class="text-container">
            <p>Your introduction paragraph goes here. Keep it concise and engaging to draw in your readers. Highlight your key skills and experiences.</p>
            <p>Your second paragraph can delve deeper into your background, passions, or specific areas of expertise. Feel free to personalize this section.</p>
        </div>
    </section>
    <section id="projects">
        <h2 class="centered-heading">Projects</h2>
        <div class="row justify-content-center">
            <div class="col-md-4"> 
                <div class="card mb-4">
                    <img src="images/projects/1.jpg" class="card-img-top" alt="Project 1">
                    <div class="card-body">
                        <h5 class="card-title">Project 1</h5>
                        <p class="card-text">Lorem ipsum dolor sit amet, consectetur   
 adipiscing elit. Integer posuere erat a ante.</p>
                        <a href="#" class="btn btn-primary">Blog   
 Post</a>
                        <a href="#" class="btn btn-secondary">Source Code</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4"> </div> 
            <div class="col-md-4"> </div>
        </div>
    </section>

<style> /* General Styling */
body {
    font-family: sans-serif; /* Choose a modern font */
    margin: 0; 
}

#about {
    padding: 80px 0; /* Top/bottom padding for spacing */
    text-align: center; /* Center all content */
}

.centered-heading {
    font-size: 3em; /* Large heading size */
    margin-bottom: 20px; /* Space below heading */
}

/* Image Styling */
.profile-image {
    width: 200px; /* Adjust as needed */
    height: 200px; 
    border-radius: 50%; /* Creates a circle */
    border: 4px solid #ddd; /* Optional border */
    object-fit: cover; /* Ensures image fills the circle without distorting */
    margin-bottom: 20px;
}

/* Text Styling */
.text-container {
    max-width: 600px; /* Comfortable reading width */
    margin: 0 auto; /* Centers the text container */
    line-height: 1.6; /* Improves readability */
}
</style>
</body>
</html>
