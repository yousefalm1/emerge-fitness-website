# _Emerge Fitnees_

Emerge Fitness is a website for a gym located in Coventry UK. This website is meant to help clients who visits the site to see what the gym offers, who the coaches are, what our the opening hours, what our mission is and a way for them to contact us if they have any questions.

---

## Technologies used

- HTML
- CSS
- Google Fonts
- Font Awesome Icons

---
## Features

### Home page

### Navigation (Desktop):

- The logo is located in the upper left corner.
- The Home, Gallery, and Contact links are located at the top left corner of the page.
  - Home: Clicking it takes you to the homepage.
  - Gallery: Clicking it will take you there
  - Contact: Clicking on it will take them to a form they may use to get in touch with the business.
- The three navigation links have a border around them, and when you hover over them, the background colour (#1122C34), which is utilised across the page, changes and white text appears.


### Navigation (smaller screens):

- The logo is positioned in the page's centre.
- The three navigation links have been shifted to the page's centre, beneath the logo.
- The border of the navigation links shrinks to meet the reduced dimensions.
- To fit smaller devices, the navigation link gets smaller and closer together.
- The navigation links continue to have a hover effect.


![NavBar desktop](assets/images/nav-big.png)

![NavBar smaller screens](assets/images/nav-small.png)


---


### Hero section:

- The background image of the hero section of the website features a portion of the gym. 
- On the background image, there are two different texts that are centred in the middle of the image: - The first text is the main one and says "Welcome to emerge fitness" in bold - the second text is right under the first text but is not bold and reads "State of the are faciltites in the centre of Coventry"
- A button that also leads to the contact page is located directly under the two texts.
- The button's hover effect is the same as that of the navigation links.
- The text, button, and image sizes in the hero section adjust in accordance with the screen's dimensions.

![HeroSection](assets/images/hero-section.png)

---
### About us section:

- The "About us" phrase appears in the top centre of the first section of the about page.
- The "about us" section has three boxes with grey backgrounds and boroder radii.
- Each of the three boxes holds unique information:
  - The first box offers details about the gym's mission. 
  - Details about the gym's amenities are provided in the second box.
  Information about the gym's operating hours can be found in the third box.
- Each box has a hover feature that modifies the box shadow when it is over it.
- The three boxes are responsive as the dimensions changes.
- On a large screen, the boxes are side by side; as the screen's dimensions decrease, the boxes move to two boxes on top of one box, and additional screen reduction causes the boxes to stack on top of each other.


![AboutUs desktop](assets/images/about-us-big.png)

![AboutUs smaller screens](assets/images/about-us-small.png)

---

### Meet the coaches:

- The phrase "meet the coaches" is located in the section's top centre.
- There are three coach cards in this area.
- The background of these coach cards is white, while the lettering is black.
- Coach cards come with information on the coaches as well as an image of the coach at the top of the card.
- The coach car also includes a hover effect, which alters the size and changes the background colour (#1122C34), text colour, and background colour to white.
- The three card are resposive when the dimensions of the page changes.
- On a large screen, the boxes are side by side; as the screen's dimensions decrease, the boxes move to two boxes on top of one box, and additional screen reduction causes the boxes to stack on top of each other.


![MeetTheCoaches desktop](assets/images/meet-the-coaches-big.png)

![MeetTheCoaches smaller screens](assets/images/meet-the-coaches-small.png)

---

### Footer:

- The Emerge Fitness logo can be found in the footer section, centrally located.
- The social media links (Instagram, Twitter, Facebook, and Youtube) are located beneath the logo.
- The social meida links are animated to get bigger when it is hovered over.
- The footer is responsive to when screen dimensions get smaller.

![Footer](assets/images/footer-big.png)

![Footer](assets/images/footer-small.png)

---

### Gallery:

- Same navigation and footer as home page.
- Contains images of clients working out.
- The gallery is repsonsive to all screen dimensions
![Gallery](assets/images/gallery.png)


---

### Contact page:

- The nav bar on this page matches that on the home page.
- This page contains a contact form with the following fields: - First and last names as text inputs - Email address as a text input.
  – A single tel input for the phone number.
  - Three checkboxes on a radio for selecting the reason for contacting.
  - A text box where potential customers can list any additional justifications for contacting.
  - A submit button that, when clicked, turns grey.
- This page responds appropriately to all screen sizes.

![Contact Form](assets/images/contact-form.png)

--- 

## Testing

- I tested the website on Chrome, Safari and Firefox.
- I tested all the links and button included on the website on all browseres
- I used the dev tools to test to confirm the website is responsive.
- I also used a website called https://responsivedesignchecker.com/ which was recommended by my mentor to test the responsiveness.


---

### Bugs

- The first bug was with the header this was beacuse when i started wrting the code for it i didnt use flex box and as i counitued with the project i started using flex box, this causes problmes with responsiveness of the page. Therefore i had to rewrite the the css for the header using flex box.
- The secound bug was the footer logo and address was moving left on smaller screens,i fixed this by using a media query and using text align: center.
- The third bug was for the hero image i added backgroud-size this made this image looked streched and no aappealing to look at therofre the soultion i used was removing the backgroud size which made the imgae look way better.

---

### Validator testing

#### HTML:
- Index.html: No errors or warnings were found when passing through the official W3C validator.

![Index W3C](assets/images/index-html-checker.png)

- Gallery.html: No errors or warnings were found when passing through the official W3C validator.

![Gallery W3C](assets/images/gallery-html-checker.png)

- Contact.html: No errors or warnings were found when passing through the official W3C validator.

![COn W3C](assets/images/contact-checker.png)

#### CSS

- No errors or warnings were found when passing through the official W3C validator.

![Gallery W3C](assets/images/css-checker.png)

####  Accessibility and performance

- I used the lighthouse feature in devtools to confirm the website is:
  - Performing well.
  - Accessible
  - Font and colors are readable.

#### Lighthouse (desktop):


#### Lighthouse (mobile):

---

### Deployment

- The website was deployed on GitHub pages the link is is #

---

### credits

- ### Content
   - I used MDN (https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/linear-gradient) for help to make the white text show since the backgroudd img made it hard to see the text. 

   - I used MDN (https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow) to help understand box shadow. 

  - To make the cards a watched a youtbe video (https://www.youtube.com/watch?v=qXRYMdvq_Dc) which helped me grasp the idea on how cards words and made changes to fit the idea of my website.

  -  I used W3C (https://www.w3schools.com/css/css3_transitions.asp) to help with transition

  -  I got help by my mentor to understand how to make it get a bit bigger.

  - I Used code the gallery i used code from the love running project and made some modifiications.

  - To make the cards a watched a youtbe video (https://www.youtube.com/watch?v=qXRYMdvq_Dc) which helped me grasp the idea on how cards words and made changes to fit the idea of my website */
  -


- ### Media
   - All the imgage used in this website was taken from https://www.pexels.com/



### Wire Frames

#### Home Page desktop:
![Home Page Desktop](assets/images/home-desktop-wire.png)

#### Home Page Mobile:
![Home Page Mobile](assets/images/home-mobile-wire.png)

---

#### Gallery Page Desktop:

![Gallery Page Desktop](assets/images/gallery-desktop-wire.png)

#### Gallery Page Mobile:
![Gallery Page Mobile](assets/images/gallery-mobile-wire.png)

---

#### Contact Page Desktop:
![Contact Page Desktop](assets/images/contact-desktop-wire.png)

#### Contact Page Mobile:
![Contact Page Desktop](assets/images/contact-mobile-wire.png)

---