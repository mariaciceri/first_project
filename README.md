# Climbing Rox

The Climbing Rox is a web page for climbers of any level to read more about the sport, provide help with equipment they will buy, and/or routes they are going to visit. 
Access the webpage [here](https://mariaciceri.github.io/first_project/).

![Am I responsive display of the project page](assets/images-doc/responsive.png)

## User Story
### First Timers

+ When visiting the page for the first time, the user can read about the authors in _Home_;
+ The user can easily access the content of the page and navigate through the different sections; 
+ The user can easily find the section containing the articles and choose the one they are interested in;
+ The user can subscribe and follow the authors to be up-to-date with new content being released.


### Returning and Frequent Visitors

+ The user can easily send a question to the authors and contact them; 
+ The user can check if there are any new articles; 


## Features

### Navigation Bar

+ Positioned at the top of the page, below the cover image.
+ Contains the following links on the center-right:
    * Home/Advice; 
    * Get Help; 
    * Follow Us; 
    
+ Animated hover effect. 
+ Call to action:
    * _Get Help_ will open a popup window to contact the authors with a question. 
    * _Follow Us_ will scroll down to the footer where the user will find icons to click and be redirected to social media pages. These pages will open in another tab. 

![Navbar with home, advice, get help and follow us buttons](assets/images-doc/navbar-article.png)
![Navbar with home, get help and follow us buttons](assets/images-doc/navbar-advice.png)
    
+ Back to the top button is always visible on the right side of both pages. 


### Get Help Popup Window

+ When _Get Help_ navigation tag is clicked, the hidden content shows up, as a popup window, darkening the whole page behind.
+ The user has to provide full name, email and fill up the text area to be able to submit the form.
+ A feedback message then is triggered, letting the user know that the message was received.
+ A closing button is placed in the top-right corner of both popups.


![Get help pop up window with full name, email, and text area boxes](assets/images-doc/popup1.png)
![Feedback message after submitting a question](assets/images-doc/popup2.png)

### Hero Section.

+ Hero sections have a cover background image, a headline, a subtitle and a navbar.

![Background image with a person climbing with a yellow sky](assets/images-doc/home-hero.png)
![Background image with a person hanging with a climbing tent and with a orange sky in the backgorund](assets/images-doc/hero-the-rest.png)

### Footer for Home and Advice pages

+ The footer contains links to social media pages that will open in a new tab.

![Footer with background in black, sentence "Follow us on:" and instagram, X and spotify icons](assets/images-doc/footer.png)


## Home Page

+ Introduction of the sport (climbing) and the authors.
+ Brief explanation of the purpose of the webpage.
+ The page is responsive: if the screen size is bigger than mobile screens, the About Us text comes next to the picture.


![First part of the Home page](assets/images-doc/rox1.png)
![About us and footer of Home page](assets/images-doc/rox2.png)


## Advice Section
### Introduction

+ A more detailed explanation of the web page purpose;
+ Articles available to read are displayed with an image and a title. On larger screens, there is a subtitle and even a hover effect for desktops and laptops.

![Introduction and rticles available to read displayed with an image, a title and a subtitle](assets/images-doc/advice-section.png)

## What are the types of Sport Climbing article

+ The article has the same hero section as the advice page and other articles.
+ Introduction of the content of this article;
+ Direct link to parts of the content;
+ The informational text is separated into three sub-categories and a conclusion;

![Hero section with name and intro of the article](assets/images-doc/climbing-types-hero.png)


## How to choose climbing shoes article article

+ The article has the same hero section as the advice page and other articles.
+ Text explaining the purpose of the following content.
+ Direct links to parts of the content and to the navbar.
+ The informational text is separated into three sub-categories and a conclusion.
    
![Hero section with name and intro of the article](assets/images-doc/choosing-shoe-hero.png)


### Features left to implement

+ Make the popup window open every time _Get Help_ is mentioned so the user doesn't need to go up to the navbar.
+ When the user can see the whole page and click on follow us, the footer blinks or gives feedback showing that the links are there.
+ Add source of images to the browser to choose which is adequate to the screen size of the user, this way the performance can be enhanced for the articles;


## Technologies Used

+ [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) is the foundation of the pages;
+ [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) adds the style and layout of the pages;
+ [CSS Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) adds responsiveness to the elements on the pages;
+ [Gitpod](https://gitpod.io/) with [VScode](https://code.visualstudio.com/) desktop extension is the IDE for the project;
+ [Git](https://git-scm.com/) is the main tool to version control the webpage;
+ [Github](https://github.com/) is where the pages are hosted.
+ [Github Pages](https://pages.github.com/) is where the website was deployed;
+ [Font Awesome](https://fontawesome.com/) is used for icons throughout the entire project.
+ [Licecap](https://www.cockos.com/licecap/) is used to create gifs to show responsiveness.

## Deployment

### Deployment to GitHub Pages

+ The page was deployed in the early stages to GitHub pages. The steps to deploy are as follows:
    * In the GitHub [repository](https://github.com/mariaciceri/first_project), navigate to the Settings tab;
    * On the right-hand side in the menu, click on pages;
    * In Source check if "deploy from branch" is selected, then below it, in Branch, select "main" and save it;
    * To access it for the first time, go back to Code in the main navbar and on the left-hand side scroll down to deployments, click there and open the page;

### Local Deployment

+ In order to make a local copy of this project, you can clone it. In your IDE Terminal, type the following command to clone my repository:

git clone https://github.com/mariaciceri/first_project.git

## Responsiveness

    + All the pages are responsive. To see and read more, refer to [TESTING.md](TESTING.md)

## Credits

### Content

+ First boilerplate code was taken from [Love Running](https://github.com/mariaciceri/love-running-practice) project of Code Institute;
+ Popup window inspiration and code was taken from [Dev](https://dev.to/pachicodes/creating-a-css-modal-window-pop-up-step-by-step-1f59) and [Beyond the Sketch](https://www.beyondthesketch.com/developer/css-only-modals/);
+ The text and advice section were inspired by [Rei coop](https://www.rei.com/learn/expert-advice/rock-shoes.html?srsltid=AfmBOorRz0dMXRcebMmKl2vc8nr7PmiiQbzrWg8WhAQbV86vnILnHNRb);
+ Footer icons were taken from [Font Awesome](https://fontawesome.com/).
+ New knowledge and usage of features for this project were taken from [MDN web docs](https://developer.mozilla.org/en-US/)


### Media

+ Images were taken from [Unsplash](https://unsplash.com/), [Pexels](https://unsplash.com/) and free trial of [Adobe Stock](https://stock.adobe.com/se/search?k=%22climbing+shoes%22&search_type=recentsearch);
+ Converting from jpg to webp was done on [Convertio](https://convertio.co/jpg-webp/);
+ Cropping and resizing was done on [Aspose](https://products.aspose.app/imaging/image-crop/webp).






