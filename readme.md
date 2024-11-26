Creating static web pages and deploying them to GitHub Pages is a great choice for hosting small projects, portfolios, or documentation. Here's a step-by-step guide:

1. Plan Your Website Structure

Decide on the layout and structure of your site:

    Number of pages (e.g., Home, About, Portfolio, Contact).
    Navigation bar linking the pages.
    Visual style: colors, fonts, and overall design.

2. Set Up Your Project

   Create a new folder for your project.
   Inside the folder, create the following files:
   index.html: Main page.
   Additional .html files for other pages.
   style.css: For custom styles.
   script.js (optional): For interactivity.
   assets/: A subdirectory for images or other media.

3. Build the HTML Pages

Write clean, semantic HTML5 code. Here's a basic example for index.html:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Pages Site</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Welcome to My Website</h1>
        <p>This is my GitHub Pages site!</p>
    </main>
    <footer>
        <p>© 2024 My Website</p>
    </footer>
</body>
</html>

4. Style with CSS

Create a simple style.css:

body {
font-family: Arial, sans-serif;
line-height: 1.6;
margin: 0;
padding: 0;
background: #f4f4f4;
color: #333;
}

header {
background: #333;
color: #fff;
padding: 10px 0;
}

header ul {
list-style: none;
padding: 0;
display: flex;
justify-content: center;
}

header li {
margin: 0 10px;
}

header a {
color: #fff;
text-decoration: none;
}

footer {
text-align: center;
padding: 10px;
background: #333;
color: #fff;
}

5. Create a GitHub Repository

   Go to GitHub and log in.
   Click on New Repository.
   Name your repository (e.g., my-website).
   Initialize it with a README.md file.

6. Upload Your Files

   Clone the repository locally:

git clone https://github.com/your-username/my-website.git

Copy your project files into the cloned repository folder.
Push the changes:

    git add .
    git commit -m "Initial commit"
    git push origin main

7. Enable GitHub Pages

   Go to the repository on GitHub.
   Click on Settings > Pages.
   Under Source, select the branch (e.g., main) and the root folder.
   Click Save. GitHub will provide a link to your live site (e.g., https://your-username.github.io/my-website/).
