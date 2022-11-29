# Marius Bodochi 
- __Actor and Artistic Director at TNB Bucharest__

This site is meant to serve as a platform for the ones that love the Dramatic Art and want to understand more about the presented actor and get in touch with him.

The goal of this platform is to briefly introduce the fan to the work of this artist 
and to facilitate the option of further discovering the work of Marius Bodochi through the use of social media and the Bucharest National Theater website! 

![Home Screen](documentation/homeimg_full.png)

## Features

- As briefly described above the purpose of this website is to serve as a quick introduction for the Artist, but also to facilitate the conection between the Dramatic Art enthusiasts and the actor.
- Besides the immediate features this website also presents itself as a quick and easy to use platfom that enables not only the fans, 
but any curios minds to keep track of the artist, his latest works, any public apparitions and of course all possible future projects!
- The brief introduction is made through the Home Page in the About section, which is also accompanied by a visual variety that opens a photo gallery with the use of Media Tab in the Menu bar.
- At the bottom of the page, the user can find quick links to the artists Social Media accounts which will enable further research about the work of the artist. 
- As an extra styling feature the Mask Icon situated at the left of the Menu will change the color from red to gold when hovered over. 
- This styling feature is also repeated throughout the page when using the mask icon on the About section and also when using the institution icon for the TNB section above the footer at the bottom of Home page.

### Build Features

- __Navigation__ 

- On all three pages at the top, the user can find the Navigation bar which will facilitate access to the Home page (with the "About" Section included), the Media and the Contact page.
- On the left side of the Navigation bar, there's also included an icon, that has the same functionality as the Home page button. 
- This Theater Mask symbol also serves as an estetic element which is supposed to be well integrated in the design of the website.  
- The Navigation bar is also fully responsive and will adapt according to the screen size.

![Navi Bar](documentation/navi_bar.png)

- __Home page top__

- Below the Nav bar, at the top of the Home page, the user can find an antic roman theatre image,
that is overlayed with the Artist name and a quick introduction to his career title & the institution he's currently hired with.
- The color combination and the black and white picture are supposed to introduce the user to the Artist and that has a long fruitful career in the Dramatic Art.
- This combination, while introdcing the Actor it also sets the stage for the next section in a catchy and nostalgic way that transposes the user in the fascinating world of thatre and film!   

![Introduction](documentation/intro.png)

- __About Section__

- The About section is segmented in three parts, from left to right. 
- The first section on the left presents a brief introduction about the artists career and his biography.
- The middle section is features an expressive portrait picture of the Artist which is also in black and white, in order to fit the styling and the feel of the website.
- The third section or the section on the right side, presents a remarkable quote about the artist written by the prolific writer and arts critic from Romania, Mihaela Dordea.
- As an important note for the About section, since is situated on the Home Page (below the introduction image), the user is presented with a handy feature that allows the page to scroll back to the top simply by clicking the stylish theater mask icon situated to the right of the About title.

![About](documentation/home_about.png)

- __National Bucharest Theater Section__

- This section is minimal in design and besides the esthetical aspect it's also meant to serve the purpose of redirecting the user to the Actor profile over to the Bucharest National Theatre website. 
- This functionality is met by clicking on the red institution icon situated above the "BUCHAREST NATIONAL THEATRE" title. 

![BNT](documentation/tnb_sec.png)

- __Footer Section__

- This section provides links to the Social Media accounts that feature the Artist and his work. 
- By accessing these links the user can research the past work of the Actor and stay updated with regards to the current and future projects that the Artist is working on.
- All links are set to open in a new browser tab in order to ease the user navigation. 
- The footer section is of course present at the bottom of all three pages that are accessible through the Navigation bar. 

![Footer](documentation/footer.png)

- __Media Tab__

- This tab is supposed to provide a collage of images that represent the highlights of the Artists career on stage or on film sets
- The expressive gestures, poses and attitudes manifested by the actor through the intepreted roles in these picures should provide a clear representation of the artists abilities and acting! 

![Media](documentation/mediascreen.png)

- __Contact Tab__ 

- The Contact tab serves as a direct communication tool that will inable the user to get in touch with the Artist for any queries and remarks.
- This page should also serves as a useful tool for any booking agency or project representatives that would like to send a proposal to the Artist.
- The form presented on this page requires the user to input the their name and contact email before typing in the desired message.
- At the bottom of the form there are two stylized inputs, one for submitting the message and the other one for reseting the form. 
- Both buttons are stylized in the same manner as the Mask Icon in the Navigation bar.

![Contact](documentation/contact.png)

### Followup Features

- A first followup feature that could improve the user experience would be the ability to preview each photo separately in the Media gallery. 
  - This feature would enable the user to scroll through the gallery from the preview perspective.  
- An extra useful functionality that could be implemented in this project would be a Calendar tab, that would provide the user with a clear overview of the Artists schedule,
where the already booked and the free dates are highlighted in a distinct way.

## Testing 

- The functionality and scaling testing was done extensively through the inspector toll on the Google Chrome and on Microsoft Edge browser.
- It was concluded that the scaling and functionality works perfectly well from 4K to 1024px and all the way down to 375px.
- Below the screenshots from both browsers can be seen:
  - ### Microsoft Edge
  - ![edge_laptop1024](documentation/scaling/edge_home_laptop1024.jpeg)
  - ![edge_tablet768](documentation/scaling/edge_contact_tablet768.jpeg)
  - ![edge_mobile425](documentation/scaling/edge_media1_mobile425.png)

  - ### Google Chrome
  - ![chrome_laptop1024](documentation/scaling/chrome_contact_laptop1024.png)
  - ![chrome_tablet768](documentation/scaling/chrome_media_tablet768.png)
  - ![chrome_mobile375](documentation/scaling/chrome_home_mobile425.png)

### Bugs & issues
  - One of the main challenges was to keep the [BNT] text box section on the Home Page centered when scaling down to smaller screens.
    - The solution for this problem came with the use of @media scaling and by using percentages for the width and the left margin. 

### Extra testing

- Extra testing was performed for the overall score of the website on different levels with the use of Lighthouse found inside the inspector tools in Google Chrome.
- The results for the Home, Media and Contact page were as follows:

- ![Lighthouse-Home](documentation/lighthouse_test.png)

- ![Lighthouse-Media](documentation/lighthouse_media.png)

- ![Lighthouse-Coontact](documentation/lighthouse_contact.png)

### Validator Tests

- For the HTML files (index.html, media.html & contact.html):
  - No errors were returned when passing through the official 
  - [W3C validator-index.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Ftrikalex.github.io%2Fpp1-actor-mb%2Findex.html) 
  - ![index.html](documentation/validator/index_valid.png)

  - [W3C validator-media.html](https://validator.w3.org/nu/?doc=https://trikalex.github.io/pp1-actor-mb/media.html)
  - ![media.html](documentation/validator/media_valid.png)

  - [W3C validator-contact.html](https://validator.w3.org/nu/?doc=https://trikalex.github.io/pp1-actor-mb/contact.html)
  - ![contact.html](documentation/validator/contact_valid.png)

- For the style.css file: 
  - No errors were found when passing through the official [(Jigsaw3) CSS-validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Ftrikalex.github.io%2Fpp1-actor-mb)
  - ![style.css](documentation/validator/css_valid.png)

### Unfixed Issues

- **About section** - the text boxes will display slightly off centered from 1024px down to 320px 

## Deployment

The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the [GitHub repository](https://github.com/trikalex/pp1-actor-mb), navigate to the Settings tab 
  - From the source section drop-down menu, select the **Main** Branch, then click "Save".
  - The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found [here](https://trikalex.github.io/pp1-actor-mb/)

### Local Deployment

You can clone the repository by following these steps:

1. Go to the [GitHub repository](https://github.com/trikalex/pp1-actor-mb) 
2. Locate the Code button above the list of files and click it 
3. Select if you prefer to clone using HTTPS, SSH, or GitHub CLI and click the copy button to copy the URL to your clipboard
4. Open Git Bash or Terminal
5. Change the current working directory to the one where you want the cloned directory
6. In your IDE Terminal, type the following command to clone my repository:
	- `git clone https://github.com/trikalex/pp1-actor-mb.git`
7. Press Enter to create your local clone.

Alternatively, if using Gitpod, you can click below to create your own workspace using this repository.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/trikalex/pp1-actor-mb)

## Credits 

- ### Code
    - Mainly the lessons and modules specifically the Coders Coffeehouse project and Love Running were used as a support in the creation of this Artist website.
    - Also there was partly reliance on the [W3schools](https://www.w3schools.com/default.asp) website when checking different HTML or CSS styling coding procedures.
    - More precisely for the Flexbox features the following page was used as inspiration [Flexbox](https://www.w3schools.com/css/css3_flexbox.asp)
    - The Footer **HTML** code that includes the Social Media links was copied from the _Love Running_ project, however some the used icons were replaced with different ones that better fit the style of this website!

- ### Content
    - The biography & introduction text used on the left side of the About section was taken from the [Wikipedia](https://ro.wikipedia.org/wiki/Marius_Bodochi) article that presents the Actor. 
    - The quote written by the writer and art critic Mihaela Dordea on 28th of May 2010 was taken from an article that was presenting the role of Marius Bodochi in the Amadeus play [Curentul-International](http://curentul.net/2010/05/28/regal-marius-bodochi-la-opera-nationala-amadeus/).

- ### Media
    - The Background images for the Home page and the Contact form were taken from the official free to use stock photos website [Pexels](https://www.pexels.com/)
    - The icons used in the Menu bar and on the Home page were obtained from the free stock ofered by [Fontawesome](https://fontawesome.com/search?o=r&m=free)
    - Most of the photos included in the Media and Home tab were provided by the artist but also another batch were taken from the artist profile on National Bucharest Theatre [TNB](https://www.tnb.ro/ro/marius-bodochi) and from Google images search. 
