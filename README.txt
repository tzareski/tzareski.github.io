General:

This website is composed of 4 webpages. "index.html" is the homepage, "about.html" 
is about me (Tom Zareski), "projects.html" displays my various projects, and 
"media.html" displays images, videos, and audio of those projects.

Although the content of each webpage varies, the top navigation bar is universally 
at the top.This allows the user to easily navigate through the website regardless 
of which webpage they are on.

**NOTE**
- I have resused the HTML from assignment 1 for this assignment
- The combinator locations can be found on line 63 of this page

Functions:

The top of each .html webpage file starts with this code:

<head>
    <meta charset="UFT-8">
    <title>   x    </title>
    <link rel="icon" href="images\tomza_favicon.jpg">
</head>

Where "x" is replaced with the title of the webpage, and the "href" link corresponds 
to the location of the fav-icon image.

The <center> tag is parent to everything within the body, thus everything that is seen
on the webpage is centered. This keeps the webpage more organized and easy to follow.

The <table> tag is also used for organization of content, whether it be text, images, 
videos, or audio.

The <body> tag of each .html file holds this code:

    <nav>
        <div class="navbar">
            <div class="logo"><a href="index.html"><img src="images\TOMZA_5.jpg" alt="homepage link" width="90"></a></div>
            <div class="navRight">
                <div class="about"><a href="about.html">about</a></div>
                <div class="projects"><a href="projects.html">projects</a></div>
                <div class="media"><a href="media.html">media</a></div>
            </div>
        </div>
    </nav>

This is the code for the top navigation bar. The first cell in the table holds a jpeg image. 
This image acts as a link back to the hompage. The other cells in the table hold text links 
to their respective webpages.

The <hr> tag inserts a through line. This is for the organization of webpage sections.

The <iframe> tag is used to embed YouTube videos into the webpage.

The "controls" within the <audio> tag embeds an audio control bar into the webpage, so the user 
has control over the linked audio.

The "target="_blank"" modification within the <a> tag is used with external links to open the link in a 
seperate browser window. This is done so the user stays on the webpage, and can visit the external site
when they are ready.

<br> tags are used as a line break throughout the website. This helps with overall design and organization.

Locations of Combinators in "style.css"

Universal selector: line 1

Multiple selector: line 59

Child selector: line 120

Sibling selector: line 137

Adjacent selector: line 134

Attribute selector: line 140

Pseudo-element selector: line 155

References: 

[1] eastcoastdna. 2023. persephone - angela (live) @ Woodside Beverage Room and Gril. Video. (8 February 2023). Retrieved February 9, 2023 from https://www.youtube.com/watch?v=AzQDUiCCRHo&ab_channel=EastCoastDnA

[2] persephone_band. 2023. Instgram. Retrieved from https://www.instagram.com/persephone_band/

[3] Persephone. 2023. Spotify. Retrieved from https://open.spotify.com/artist/4lm0QUfFth7n0yPfLgz5ZL?si=Ywc_gtVtQk2pa4djC0zdWw&nd=1

[4] Persephone. 2023. Linktree. Retrieved from https://linktr.ee/persephone_band

[5] tomzaband. 2023. Instgram. Retrieved from https://www.instagram.com/tomzaband/

[6] fkaalfie. 2023. Instagram. Retrieved from https://www.instagram.com/fkaalfie/

[7] Alfie. 2023. Spotify. Retrieved form https://open.spotify.com/artist/7Gyxaixh0rQoOrsSp3za4S?si=BcVmK1yOTlWTuBmyiJMS6A&nd=1





 
