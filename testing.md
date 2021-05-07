## **Testing**

### **Automated Testing**

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

* [W3C Markup Validator] (https://validator.w3.org/) 
* [W3C CSS Validator] (https://jigsaw.w3.org/css-validator/)


### Lighthouse score

The lighthouse score in google chrome developer tools was used on each page. Results were improved for SEO by adding a meta tag in the head describing the website's content and by compressing the hero and profile images. 


[Homepage](assets/images/screenshots/lighthouse-report-homepage.png)

[About Me ](assets/images/screenshots/lighthouse-report-aboutme.png)

[Contact ](assets/images/screenshots/lighthouse-report-contact.png)

[FAQ ](assets/images/screenshots/lighthouse-report-faq.png)


## **Testing User Stories from User Experience (UX) Section**
    

 As a first-time user of the site who is considering 1-to-1 IELTS online tuition, I want:

1. Information presented in clear and easy to understand English.
    * The site's homepage consists of a navigation bar with four clear options. A simple hero image that clearly states that this is a site related to the IELTS exam.
    * A user can understand the basic premise of the website from the two headings (written in plain English) "Learn IELTS Online" and "Improve your band score with one-one lessons" as the primary service this website is offering is online 1-1 IELTS lessons. 
    * The background of all sections of the website has been designed to be minimal and free from clutter or unnecessary images in order to not distract a site user and all language has been kept to plain English as much as possible. 
    
2. Information about the tutor’s experience with the IELTS exam.
    * A site user can learn more about the teacher from the 'Learn from the best' sub-section on the homepage or visit the About Me page in which there is a profile image, a brief article about the tutor's experience and student testimonials.

3. Examples of the tutor’s teaching materials.
    * A site user can download an example of the tutor's teaching material by clicking the link in the navigation bar. 

4. Information about the tutor’s method and style of teaching.
    * The site offers an about me page which not only gives information about the tutor but also their methods of teaching. The student testimonial section also offers site users an opportunity to learn about what other students say about the tutors teaching methods and styles.

5. The ability to find the exact cost of lessons.
    * A site user can easily find the price of lessons and extra information related to timings and schedules by navigating to the FAQ page via the navigation bar or the link in the sub-section of the homepage. Upon entering the FAQ page the accordion of frequently asked question is open on the question
    what is the cost of the lessons, so that students can easily find out this key information without having to click on any of the links. 

6. The ability to communicate to the tutor my exact goals and what I need to improve.
    * A site user has the option to contact the tutor by filling in a contact form. By providing basic information about themselves and their English learning background the user can contact the tutor to book a free consultation in regards to booking lessons. There is a text area in which the student can express their goals more clearly. 
    * In the FAQ page there is also a link to the tutors email address from which the user can ask any questions not answered in the FAQ section.  

### **Browser Compatibility**

The Website was tested on Google Chrome , Internet Explorer, Microsoft Edge and Safari browsers.

### **Devices**

The website was designed on a MacBook Pro Laptop using a thunderbolt display and was tested on the following devices
* iPhone X 
* iPad 3
* iPhone 6 

### **Manual Testing Procedure**

All steps were taken on Google Chrome, Firefox, Safari and Internet Explorer on a Thunderbolt Display at two different desktop screen resolutions and subsequently an iPhone X screen, iPad 3, and iPhone 6.

### **Elements on each page.**

1. Navbar
    * Hover over each link to check hover effect is working.
    * Click IELTS 1-1 navbar brand to check it brings user to the homepage.
    * Click the **Home** link to check it brings user to the homepage.
    * Click the **About** link to check it brings user to the about me page and **About** link is selected.
    * Click the **Contact** link to check it brings user to the contact page and **Contact** link is selected.
    * Click the **FAQ** link to check it brings user to the FAQ page **FAQ** link is selected.
    * Click the  **Download** link to check it successfully downloads the Free Lesson PDF.
    * Check on mobile screen that nav bar collapses correctly into hamburger and all links work as above. 

2. Footer
    * Click the **IELTS 1-1** Logo to check it brings used back to homepage from all other pages. 

### **Homepage**

1. Hero Image 
    * Check Hero Image loads quickly and is displayed clearly.
    * Check Headings are clear and easy to read.
    * Hover over button to check hover effect works
    * Click book a session button to check it successfully takes the user to the contact page.
    * Check that headings are centred and the sub-heading and buttons are arranged beneath the central logo of the hero-image on mobile screens. 

2. Learn More Section
    * Check text is easy to read.
    * Hover over blue buttons to check if effect is working properly.
    * Check that the 3-column layout is arranged horizontally on desktop screens.
    * Check that the 3-column layout is arranged vertically on Tablet and Mobile screens.

### **About Me Page**

1. Profile Image
    * Check image loads quickly and is displayed clearly.
    * Check image is displayed on the left of the screen on desktop screens.
    * Check image is centred , below the section heading, on tablet and mobile screens. 

2. Profile text
    * Check text is easy to read and understand.
    * Check text column is aligned to the right on desktop screens .
    * Check text column is centred below the profile image on tablet and mobile screens.

3. Testimonials Section
    * Check Student's name is clear to read and is displayed before the flag icon.
    * Check flag icon is clear and is displaying correctly.
    * Check 3-Column column layout on desktop is horizontally aligned.
    * Check that the 3-column layout on tablet and mobile is displayed vertically. 

### **Contact Page**

1. Contact form

    * Click send with all inputs empty to check required field error appears on name.  
    * Click name input field to check highlighting effect is working.
    * Enter name and click send to check  that the form alerts me to enter a valid email.
    * Click email input field to check highlighting effect is working.
    * Enter email address without @ symbol to check that the form alerts me to enter a valid email address.
    * Enter invalid character after @ symbol to check that the form alerts me to enter a valid email address.
    * Click dropdown button on nationality input to check that nationality list appears.
    * Hover over nationality input to check that form asks me to select an item in list.
    * Click dropdown button on first language input to check that languages list appears.
    * Hover over nationality input to check that form asks me to select an item in list.
    * Click dropdown button on Current English Level input to check that English Level list appears.
    * Hover over Current English Level to check that form asks me to select an item in list.
    * Click dropdown button on Required IELTS score input to check that Required IELTS score list appears.
    * Hover over Required IELTS score input to check that form asks me to select an item in list.
    * Click each of the check boxes on and off to confirm that all can be selected and de-selected. 
    * Send form without inputting any text in the more information box to check that the form alerts me that it is a required field.
    * Send form with only required fields completed to check no required input messages appear. 


### **FAQ Page**

1. FAQ Accordion 

    * Check that the 'What is the price?' card is always selected and open when page loads.
    * Check that the 'What is the price?' card closes when the title or the plus symbol is clicked . 
    * Check that the plus symbol changes to a minus symbol and the 'What is the price' closes when another card is selected in the accordion.
    * Check that the 'How long is each lesson?' card opens and closes when the title or the plus symbol is clicked . 
    * Check that the plus symbol changes to a minus symbol and the 'How Long is each lesson' closes when another card is selected in the accordion.
    * Check that the 'How many lessons can I book?' card opens and closes when the title or the plus symbol is clicked . 
    * Check that the plus symbol changes to a minus symbol and the 'How many lesson can I book?' closes when another card is selected in the accordion.
    * Check that the 'Can I get a discount if I book more lessons?' card opens and closes when the title or the plus symbol is clicked . 
    * Check that the plus symbol changes to a minus symbol and the 'Can I get a discount if I book more lessons?' closes when another card is selected in the accordion.
    * Check that the 'How will the lessons be structured?' card opens and closes when the title or the plus symbol is clicked . 
    * Check that the plus symbol changes to a minus symbol and the 'How will the lessons be structured?' closes when another card is selected in the accordion.
    * Check that the 'How long will it take to reach my goal?' card opens and closes when the title or the plus symbol is clicked . 
    * Check that the plus symbol changes to a minus symbol and the 'How long will it take to reach my goal' closes when another card is selected in the accordion.
    * Check that the 'What materials do I need?' card opens and closes when the title or the plus symbol is clicked . 
    * Check that the plus symbol changes to a minus symbol and the 'What materials do I need?' closes when another card is selected in the accordion.
    * Check that the 'Can you just mark my writing and speaking?' card opens and closes when the title or the plus symbol is clicked . 
    * Check that the plus symbol changes to a minus symbol and the 'Can you just mark my writing and speaking?' closes when another card is selected in the accordion.
    



### **Bugs**

### Solved Issues 

1. On the homepage the sub-heading was too close to the centre of the hero-imgfrom resolutions widths of 452px up to 719 px  and was being slightly obscured by the shadow on the image. 

![Screenshot of subtitle placement issue](assets/images/screenshots/screenshot-subtitle-issue.png)

The cause of the issue was that the media query  set up to move the subheading below the center of the hero image was only set up for tablet resolutions and above. 
The media query was changed to incorporate resolutions from width from 452 and above screen sizes to fix the issue.


2. The IELTS 1-1 logo in the footer when hovered over would turn blue therefore making it difficult to read on the. blue background of the footer. The issue being that even though text-decoration was set to none, the colour was still set to the default blue for links. 

![Screenshot of issue](assets/images/screenshots/screenshot-footer-hover-issue.png)

The solution was to target the footer class and the hover pseudo class and add the following CSS code

```
    .footer>a:hover {
    text-decoration: none;
    color: aliceblue;}
```

3.  The most significant issue related to the buttons in the bottom section on the homepage. Early on I ran into the problem that because the text above the buttons was of differing length, the horizontal alignment of the buttons would not match due to the content above it.
    The first step I took to solve this issue was instead of using a simple bootstrap 3-column layout, I utilised the bootstrap card-deck component to help with the responsiveness. However the issue was still apparent.

![Screenshot of issue](assets/images/screenshots/screenshot-button-issue.png)

The issue was finally solved with the help of the code institute tutor support and the use of a min-height for each card body and positioning the buttons absolutely. 
 
```
.btn-blue {
    position: absolute;
    left: 50%;
    transform: translate(-50%, 0);}
```

Then media queries were used to ensure that at each breakpoint in which the cards where horizontally aligned there was enough space for the buttons to remain horizontally aligned and not overlap with the text above them.  
```
@media screen and (min-width:1440px) {
    section-details .card-body {
        min-height: 300px;
    }

    .btn-blue {
        position: absolute;
        left: 50%;
        transform: translate(-50%, 0);
        bottom: 100px
    }
}
```

4. One bug noted during the testing period was that the contents of the about me page were not taking up 100% of the width of the viewport meaning that on mobile and desktop there was always a small empty space to the right of all of the containers. When scrolling on mobile this became particularly notable. This bug was not present on any of the other pages. 

![screenshot of issue](assets/images/screenshots/about-page-container-issue.png)

The issue was solved by going through each element on the page in chrome developer tools and locating which element was causing the overspill. As the screenshot above shows, the element causing the issue was the row above the three columns for the student testimonials.

To solve the issue I separated the section heading and the three columns into their own containers and rows as shown in the code snippet below. 
```
<header class="container-fluid">
        <div class="row">
            <div class="col">
                <h2 class="text-center section-heading">What my students say</h2>
            </div>
        </div>
    </header>
    <section class="container-fluid bottom-section">
        <div class="row">
            <div class="col-lg testimonials">
```
