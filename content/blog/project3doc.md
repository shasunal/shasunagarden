---
title: Project 3 Documentation
description: Project 3 Documentation
date: 2026-05-19
tags: [""]
---
<a href="http://157.245.213.253:3000/">Live Link</a>
<br>
<a href ="https://github.com/legenddoros/utopia-project-3">Github Repository</a>

<br>
<u>Introduction</u>
<br>
<strong>Utopia </strong> is a collaborative and interactive website made up of three pages: a home intro page, a Heaven page, and a Hell page. Visitors can drag and drop images and fridge magnet style words onto a shared canvas to build their own vision of either a perfect world or a terrible one. The two pages each has its own themed landscape with empty spaces that people fill in with drawings, text, or visual compositions. What is placed cannot be deleted (unless you know the secret word). Audio can be toggled for a more immersive experience while you patch together your artwork. The site updates live and multiple users can create together in real time. Utopia is a constantly changing collective artwork website shaped by everyone’s ideas of utopia and its darker counterpart. 

<br>

<u>Our Inspiration</u>
<br>
For inspiration, we looked at projects like <a href ="https://tilde.town/~kc/blackout/">Blackout </a> and <a href ="https://www.reddit.com/r/place/">r/place</a>. Blackout inspired the text part of our project because users can reveal or hide words to create new meanings and poems. It gave us the idea for the fridge magnet style drag-and-drop text where people can move words around freely on the canvas. We also took inspiration from r/place because of its collaborative and constantly changing nature(Until it ended). We liked the idea of a shared space where many people can contribute at once and shape the environment together over time.
<br>
Originally we were going for more of a pixel art aesthetic as shown in our figma moodboard. Later on, we started adding more variety, like the hand drawn artwork made by Scott, which made the project feel more alive. The final look became a mix of pixel art, digital drawings and collage-like images. 
<br>
When we looked for references and images online we mostly used words connected to the mood of each page. For the Heaven page, we searched things like “heaven" “nature” “beauty” because we wanted peaceful imagery. For the Hell page, we used keywords like “hell” “darkness” “evil” to find things that feel unsettling. Many of the keywords just came from thinking about the emotions and atmosphere we wanted each world to have.

<br>
<u>Figma, Video, Outside Resources </u>
<br>

<a href ="https://www.figma.com/design/RylgUb43PS4ibS0j85oNb8/Project3?node-id=13-5&t=J5xZyB9sMzDYkIiV-1">Figma</a>
<br>
<a href = "https://drive.google.com/file/d/1pl3q_01WQZuUvJlcIjreTDuDyFL3Fbx8/view?usp=sharing">Video Demo</a>
<br>
<a href = "https://docs.google.com/document/d/1aZi2pKwdt_nI5V0ACvpAXCNoK8JgsB8bSiOLQOixAkE/edit?usp=drivesdk">Outside Resources</a>


<br>

<u>Technical Process</u>
<br>
We first started by building rough layouts for each page using Nunjucks and CSS. Early on in the project we focused a lot on structure and figuring out how users would actually interact with the project. We were also gathering a database of images and words that people could interact with. 
<br>
One thing we were conflicted over was how the words were going to be presented on the canvas. At first we thought about scattering all the words directly across the canvas so people would have to search all over the canvas for the right word. An alternative was to place the words in a side panel that users could pull from. We evntually went with the side panel and added some randomness into it. A limit was added to how many words appear at once along with a refresh button that generates a new set of random words. It forces people to work with limited language and search for combinations they normally would not think of.
<br>
We also thought about whether the Heaven and Hell page should exist on the same page or as separate spaces. Having them combined into one page felt crowded so we split them into two pages with different themes, music, images, and text. I think this decision helped the project feel more immersive and gave people a clearer direction when adding something to either pages.
<br>
Another thing we talked about was whether people should be able to delete images freely. But we realized that could easily lead to people destroying other users work. So we added a hidden delete function that people can discover on their own *wink* which keeps some unpredictability without making the whole canvas a complete free for all.
<br>
One last thing we changed was the background of the canvas itself. At first the canvas was blank and it felt too empty and didn’t really push the themes of Heaven and Hell enough. So we created large scrollable landscape canvases for both pages. The landscapes have transparent holes and blank areas scattered throughout them that are like open spaces for people to fill with images, drawings, or text. Behind the landscape  we added a still checkerboard PNG with black or white spots depending on the theme of the page. The background peeks through the transparent areas as the user explores the landscape and gives the page a little more movement and texture instead of feeling flat.

<br>
<u>My Contribution</u>
<br>
I worked on the front-end of our website including finding and editing images, creating the canvas background for the Heaven and Hell pages, and css/html. I used Pixabay to source my images and Photoshop for editing. 

<br>
<a href = "">Scott</a>
<a href = "">Daniel</a>
<a href = "">Werner</a>