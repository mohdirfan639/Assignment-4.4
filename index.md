Assignment 4.4 — Metadata & Page Setup
1. Updated HTML code
Create or update your index.html file with the following code.


<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Character encoding -->
    <meta charset="UTF-8">

    <!-- Mobile responsive viewport -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Page title -->
    <title>My Web Project | Home</title>

    <!-- Page description -->
    <meta name="description" content="Welcome to my web project. Explore my website and learn more about its content.">

    <!-- Favicon -->
    <link rel="icon" type="image/png" href="images/favicon.png">

    <!-- CSS stylesheet -->
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

    <header>
        <h1>Welcome to My Web Project</h1>
    </header>

    <main>
        <p>This is my updated HTML page with proper metadata and page setup.</p>
    </main>

    <footer>
        <p>&copy; 2026 My Web Project</p>
    </footer>

</body>
</html>
2. Folder structure
Arrange your project files like this so that the CSS and favicon paths work correctly.

Assignment-4.4/

index.html

css/

style.css

images/

favicon.png

If your CSS or image files are in different folders, change the paths in your HTML accordingly. Make sure favicon.png actually exists.

3. Metadata code for submission
Submit this section separately as your metadata code.


<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Web Project | Home</title>
<meta name="description" content="Welcome to my web project. Explore my website and learn more about its content.">
<link rel="icon" type="image/png" href="images/favicon.png">
<link rel="stylesheet" href="css/style.css">
What each tag does
Tag

Purpose

charset="UTF-8"

Supports a wide range of characters and symbols.

name="viewport"

Helps the page display correctly on mobile devices.

<title>

Sets the title shown in the browser tab.

name="description"

Provides a short description of the page for search engines.

rel="icon"

Displays the favicon in the browser tab.

rel="stylesheet"

Connects the external CSS file.

4. Add a favicon
You need an actual image file named favicon.png inside your images folder.

If you do not have one, you can create a simple square icon using Paint or another image editor. Save it as a PNG image, ideally at 32 × 32 pixels.

To verify it:

Open index.html in Chrome or another browser.

Look at the browser tab and check for your favicon.

If it does not appear, verify the image path and refresh the page. You may need to clear the browser cache.

5. Verify your CSS
Create css/style.css with this simple styling if you need a stylesheet to test.


css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 20px;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #2563eb;
    color: white;
    padding: 20px;
    text-align: center;
}

main {
    padding: 20px 0;
}

footer {
    text-align: center;
    padding: 10px;
}
6. Submission checklist
Assignment progress

0 of 7


Updated every HTML file with UTF-8 encoding

Added the viewport meta tag to every HTML file

Added a meaningful title and description to each page

Added a working favicon

Verified CSS links and file paths

Captured a browser screenshot showing the favicon

Included the metadata code in the submission
