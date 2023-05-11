# North-Holland Dunes

This site is intended to give a first impression of the beauty of the North-Holland dunes and to encourage you to explore the very diverse hiking routes and perhaps even book a guide for a guided walk with more information.

![Noth-Holland Dunes](assets/images/readme/mock-up-screens.JPG)

## Features

### Existing features

- __Navigation Bar__
  - The navigation bar contains links to all five sections of the site: the logo leads to the Landing page image section, the other links respectively to the About section, Explore section, Impressions section and Contact section.
  - This section will allow the user to easily navigate from section to section across all devices.
  - The navigation bar is fully responsive. On smaller devices, the hamburger menu appears with an expanded menu bar.

![Nav Bar Desktop](assets/images/readme/screenshot-navigation-bar.JPG)
![Nav Bar Mobile Closed](assets/images/readme/screenshot-mobile-menu-closed.JPG)
![Nav Bar Mobile Open](assets/images/readme/screenshot-mobile-menu-open.JPG)

- __Landing page image__
  - The landing includes a photograph with text overlay that shows the goal of the whole website "Dunes in North-Holland Explore the beauty" and to allow the user to jump to the explore section with a button.
  - This section introduces the user to Dunes in North-Holland with an eye catching animation to grab their attention.

![Landing page image](assets/images/readme/screenshot-home-banner.JPG)

- __About section__
  - The About section briefly introduces the user to the nature of the North Holland dunes.
  - It also explains that you need a ticket to enter.

![About section](assets/images/readme/screenshot-about-section.JPG)

- __Explore section__
  - The Explore section shows the user the different locations of the North Holland dunes.
  - In addition, the various hiking routes can be viewed here by clicking on the button.

![Explore section](assets/images/readme/screenshot-hiking-routes.JPG)

- __Impressions section__
  - The impressions section shows three panorama pictures with a slider to show the user the beauty once again.
  - The user can control the slides himself with the navigation elements or watch the slides change automatically.

![Impressions section](assets/images/readme/screenshot-contact-section.JPG)

- __Contact section__
  - The Contact section allows the user to get in touch with us, ask questions or book a hiking route with a guide.
  - The user will be asked to submit their first and last name, an email address and a message.
  - The user must agree to the Privacy Policy.

![Contact section](assets/images/readme/screenshot-contact-section.JPG)

- __Footer section__
  - The footer section includes a link to the relevant social media site on instagram. More photos of the beauty of the dunes should be shown there and exchanged or linked among each other. The links will open to a new tab to allow easy navigation for the user.
  - The footer is valuable to the user as it encourages them to keep connected via social media.
  - The footer also contains a link to the Privacy Policy. There, users can read the privacy policy.
  - The footer also contains a copyright.

![Footer section](assets/images/readme/screenshot-footer.JPG)

- __Privacy Policy__
  - The privacy policy page includes an overview of data protection, hosting, general information and mandatory information, recording of data on this website and the used tools.

![Privacy policy](assets/images/readme/screenshot-privacy-policy-1.JPG)
![Privacy policy](assets/images/readme/screenshot-privacy-policy-2.JPG)
![Privacy policy](assets/images/readme/screenshot-privacy-policy-3.JPG)
![Privacy policy](assets/images/readme/screenshot-privacy-policy-4.JPG)
![Privacy policy](assets/images/readme/screenshot-privacy-policy-5.JPG)

- __Nav bar on Privacy Policy page__
  - The nav bar on the Privacy Policy page only contains the logo and a "back to home" link to navigate back to the main page.
  - The nav bar is fully responsive.

![Nav bar on Privacy Policy page](assets/images/readme/screenshot-navigation-bar-privacy-policy.JPG)

- __Footer on Privacy Policy page__
  - The footer section includes a link to the relevant social media site on instagram. More photos of the beauty of the dunes should be shown there and exchanged or linked among each other. The links will open to a new tab to allow easy navigation for the user.
  - The footer is valuable to the user as it encourages them to keep connected via social media.
  - The footer doesn`t contain the link to the Privacy Policy.
  - The footer also contains a copyright.

![Footer on Privacy Policy page](assets/images/readme/screenshot-footer-privacy-policy.JPG)

### Features Left to Implement

- Currently, no Hiking Routes appear when you click on the hiking routes button.
- The contact form does not send any requests yet.

## Technologies used

### Languages used

- HTML5
- CSS

### Frameworks - Libraries - Programs Used

- [Bootstrap v5.3.0-alpha3](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
  - Bootstrap to use prebuilt grid system and components, like buttons and nav bars.
- [Font Awesome](https://fontawesome.com/)
  - Font Awesome are used for the instagram icon.
- [Git](https://git-scm.com/)
  - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
- [Github](https://github.com/)
  - GitHub is used to store the project's code after being pushed from Git.

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate the pages to ensure there were no syntax errors in the project.

### Validator Testing

- __HTML__
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Fpuma13992.github.io%2Fnorth-holland-dunes%2Findex.html) and for the privacy policy page [W3C validator](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Fpuma13992.github.io%2Fnorth-holland-dunes%2Fprivacy.html)

- __CSS__
  - No errors were found when copy the styles.css in the official Jigsaw validator but when running the link, some issues showed up from the external libraries Font Awesome and Bootstrap [Results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fpuma13992.github.io%2Fnorth-holland-dunes%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=de)

Google Lighthouse was used to test Performance, Best Practices, Accessibility and SEO on both Desktop and Mobile devices.

The testing was done using the Google Chrome Browser. Chrome Developer Tools was used extensively, particularly to check responsiveness on different screen sizes. Testing was also done using Edge and Firefox on desktop, and again on an iPad Mini and iPhone using Safari.

- Responsive on all device sizes between 280px - 2600px wide
- Devices tested using the Google Developer Tools emulator:
  - iPhone SE (375x667px)
  - iPhone XR (414x896px)
  - iPhone 12 Pro (390x844px)
  - Pixel 5 (393x851px)
  - Samsung Galaxy S8+ (360x740px)
  - Samsung Galaxy S20 Ultra (412x915px)
  - iPad Air (820x1180px)
  - iPad Mini (768x1024px)
  - Surface Pro 7 (912x1368px)
  - Surface Duo (540x720px)
  - Galaxy Fold (280x653px)
  - Samsung Galaxy A15/71 (412x912px)
  - Nest Hub (1024x600px)
  - Nest Hub Max (1280x800px)

- Desktop Results:
  ![Desktop Results](assets/images/readme/screenshot-desktop-lighthouse.JPG)
- Mobile Results:
  ![Mobile Results](assets/images/readme/screenshot-mobile-lighthouse.JPG)

### Unfixed bugs

There are no unfixed bugs.

## Deployment

The website development was created in the "main" branch. This branch was deployed using GitHub Pages.

- This site was deployed by completing the following steps:

1. Open [GitHub](https://github.com/).
2. Click on the project to be deployed.
3. Navigate to the "Settings".
4. Navigate down to the "GitHub Pages".
5. Select the "main" branch and select "Save".
6. The link to the live website was ready on the top.

The live link can be found here - [Live Website](https://github.com/puma13992/north-holland-dunes)

## Credits

### Content

- The texts were taken from the following pages and translated into English:
  - [Noordhollandse Duinen](https://www.noordhollandseduinen.nl/)
  - [PWN](https://www.pwn.nl/noordhollands-duinreservaat)
  - [Holland boven Amsterdam](https://www.hollandbovenamsterdam.com/details/nl/noord-hollands-duinreservaat--4fba7d63-301b-425a-afcf-6bfc26c6d89f)
- Instructions on how to implement form validation for the contact form and the zoom in for the landing page image was taken from the Love Running project from [Code Institute](https://codeinstitute.net/).
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/).

### Media

- All photos are original, taken by me.
