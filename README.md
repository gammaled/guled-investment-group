# Guled Investment Group #

## Contents ##
---
* UX
    * Project Goals
    * User Goals
    * User Stories
    * Site Owner Goals
    * User Requirements and Expectations
    * Design Choices
        * Fonts
        * Icons
        * Colours
    * Wireframing
* Technologies Used
* Features
    * Features that have been developed
    * Features that will be implemented in the future
* Testing
* Bugs
* Deployment
* Credit
* References

## UX (User Experience) ##
---
### Project Goals ### 

The **goal** for this project is to **introduce** to **potential investors** an investment fund managed by **Guled Investment Group**, including: what an investment fund is, who manages it and commission fee structure.

### User Goals ###

* **Learn and Understand** what an investment fund is and how it works.
* **Find out** whether investing into an investment is viable and beneficial to user. 
* **Contact the company** for **more information** and request to be contacted, by providing contact details, to **learn more** about:
    * How **investment funds** work. 
    * The company's **profit sharing** and **commission structure**.
* **Learn more** about the **investment managers**: their investing background and credentials.
* **Be reassured** that the investment fund and company, that includes investment managers, are appropriately  **accredited** and **licensed**.
 
### User Stories ###

* As a **user**, I want an **informative** and **well-structured website** so I will be **properly informed without confusion**.
* As a **user**, I want to **understand** what an **investment fund** in a **language I can understand** without **too much financial jargon**.
* As a **user**, I want to be able to **easily contact the customer service** so I can ask **questions for clarification and understand better.** 
* As a **user**, I want to be **reassured** that the company and its investment managers are **well qualified** and **credible** in **investment management**.
* As a **user**, I want an **easily navigable website** that is **straight to the point** and leads me directly to the **relevant information**, avoiding **unnecessarily tedious design obstacles**.

### Site Owner Goals ###
* As a **site owner**, I want to **provide the correct information** on **investment funds** and **effectively define in simple terms** what it is. This is that **user** is **well-informed** before **making a decision** to **invest**. 
* As a **site owner**, I want to **market** to **users** about the **investment fund** we manage and **show what makes it different**, in terms of **how we manage it** and **commission fee structure**.
* As a **site owner**, I want to make it as **easy as possible** for **users** to **get in touch** for more information to understand our services better.  

### User Requirements and Expectations ###

**Requirements**
* **Navigate** the website using the navbar that scrolls to the requested section.
* The **website** should be a **one-page** website to keep users engaged. 
* A **full functioning contact form** that allows user to input **contact details and enquiries**.
* A **fully functioning learn more** button in the header of the website.

**Expectations**
* **Visually appealing website** kept **simple and easy to use** and **without** any complicated features.
* **Built** to look **professional** and with **high-quality design** should **reflect the service provided**.
* **Provide** the **most relevant information** that is **most helpful** to the user in order to **keep things short**. 

### Design Choices ###
---
When designing the website, I used the wine delivery bootstrap website from 
[Code Institute's](https://codeinstitute.net/) "Bootstrapping your next big idea" lesson 
in the User-centric Frontend Development module as a template on which I completely customised. 

**Fonts**

I tried to look for very simple fonts that were very easy to read and looked professional. 
I chose [Roboto](https://fonts.google.com/specimen/Roboto) all headings and text. 

**Colours**

I used the [Coolors](https://coolors.co/0a0a0a-575a5e-c40b08-246b94-f4f7f5) colour generator 
to find the colour scheme that suited best for the project. 

The **purpose** for each colour:
 
* **Davys Grey** (#575A5E): for navbar link font, body font and line under headings; 
* **International Orange Engineering** (#C40B08): for contact submit button, learn more button and some body text; 
* **Sapphire Blue** (#246B94): for logo and headers;
* **Cultured** (#F4F7F5): for most body backgrounds, and callout font colour;

![Color Scheme](wireframes/colour-scheme.png)

### Wireframing ###

For **wireframing**, I used [Balsamiq](https://balsamiq.com/). I used it to create **simple** wireframes 
showing the basic structure on which I built the website on. Some features maybe removed or added during 
development. 

View wireframes for each device here:

* [Desktop](https://github.com/gammaled/guled-investment-group/blob/master/wireframes/gig-desktop.pdf)
* [Tablet](https://github.com/gammaled/guled-investment-group/blob/master/wireframes/gig-tablet.pdf)
* [Mobile](https://github.com/gammaled/guled-investment-group/blob/master/wireframes/gig-mobile.pdf)

<details>
  <summary><strong>What didn't make the cut and why:</strong></summary>
  My <strong>wireframes</strong> and the website in each display format have ended up looking different to each other. This is my first project in UI/UX and I have noticed that what I planned to do did not work in reality in terms of UX/UI. My wireframes looked amazing but it did not translate so well on the different device screen. 

  This is my first project in UI/UX, as a result there were a few features that ended up taking too much time and became too difficult for me to do. 
</details>

## Technologies Used ##
---
**Languages**

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [JavaScript](https://nl.wikipedia.org/wiki/JavaScript)
* [JQuery](https://jquery.com/) 
* [Popper](https://popper.js.org/)

**Tools & Libraries**

* [Bootstrap](https://getbootstrap.com/)
* [Font-Awesome](https://fontawesome.com/icons?d=gallery)
* [Google Fonts](https://fonts.google.com/)
* [Gitpod](https://gitpod.io/workspaces/)

## Features ##
---
**Features** that have been **implemented**:
*  Simple to use **navigation bar** on all screen resolutions.
*  **Contact form** to fill out with personal details
*  **Minimalist** and **attractive** design.
* **Single page scroll** for easy navigation and use.

**Features** that will be **implemented** in the **future**:
*  Responsive **video background** in callout 
*  **Embedded videos** explaining what we do and what we offer 
*  **Google maps location** for potential clients to find our office 
*  **Social media** links

## Testing ##
---
I started by test the CSS code with the [CSS Validator](http://jigsaw.w3.org/css-validator/) and it came out **no errors found**.

I proceeded to test the HTML with the [HTML Validator](https://validator.w3.org/) and I got the following **results**: 
* Warning:

    * "Who are we?" section lacks heading
    * Contact form section lacks heading

* Fixes:

    * Changed all section header ```p``` tags to ```h2``` tags

I also tested the website by using [Lighthouse](https://developers.google.com/web/tools/lighthouse). **Performance**, **Accessibility**, **Best Practices** and **SEO** were tested then rated on a scale of 1-100. I tested both **mobile** and **desktop**:

**Mobile**
* **Performance** (62/100):
    * **Issue**: Properly size image. 
        * **Fix**: slightly reduced size of staff images.

* **Accessibility** (97/100):
    * **Contrast**: Background and foreground colours do not have a sufficient contrast ratio specifically "Learn More" button in callout. 
        * **Fix**: changed colour of button to International Orange Engineering #C40B08.

    * **Navigation**: Heading elements are not in a sequentially-descending order. 
        * **Fix**: changed ```p``` tags of "what we offer" header to ```h2```.

* **Best Practices** (100/100)

* **SEO** (100/100)

**Desktop**
* **Performance** (70/100):
    * **Issue**: Properly size image. 
        * **Fix**: slightly reduced size of staff images.

* **Accessibility** (100/100)
   
* **Best Practices** (100/100)

* **SEO** (100/100)

**Contact Form**

* I got the contact form from [Bootstrap](https://getbootstrap.com/) which is used to contact the **website owner** for more information. I customized and styled it to fit the colour scheme and design plans. The **user** enters their personal contact information in the **form field**.
* For now, there will be no feedback since it will not be possible to send a form.
    
## Bugs ##
---
There have been a few bugs encountered and I will list them below with solutions.

**During development**

* Navbar links would not position on the right hand side as planned:
    * I left it for later to figure out since it was not too important for the design. 
* Hovering over any navbar links shifts all of them upwards:
    * Still trying to figure it out and fix it.
* Unresponsive video background for callout:
    * Removed it and replaced it with an image background since it is beyond the scope of my abilities and would have wasted time. Will come back to it later on. 
*   Background image for callout would not appear:
    * Changed background-image property to background

**From validation/testing**
* Section headers had ```p``` tags instead of ```h2``` tags
    * Changed their tags to ```h2``` tags 
    
## Deployment ##
---
This project was deployed via GitHub by executing the following steps. After writing the code, committing and pushing it to GitHub:

* Navigate to the repository on github and click **Settings**.
* From there, go to the **Source section** within the Github Pages section.
* Select **master branch** on the dropdown menu, and click save.
* Now the website is live on:
```https://yourgithubusername.github.io/your-repo-name```
* Any time commits and pushes are sent to Github, the Github Pages site should update shortly after.

To run the project locally:
Click the **green Clone** or **Download button** on the Github Repository
Using the **Clone with HTTPS option**, copy the link displayed.
Open your IDE, and ensure the Git Terminal is open.
Change the working directory to the location where the cloned directory is to go.
Use the **"git clone" command** and paste the url copied in the second step.

## References ##
---
### Code References ###

Used Code Institute bootstrap basecamp code source as a template for the project.

* [Navbar](https://stackoverflow.com/questions/57980013/adding-space-between-navbar-logo-and-first-nav-link)

* [Jumbotron & background video [1]](https://stackoverflow.com/questions/34624496/bootstrap-video-jumbotron)

* [Jumbotron & background video [2]](https://stackoverflow.com/questions/46988327/set-a-responsive-video-background-for-bootstrap-jumbotron)

* [Positioning of callout and centering content [1]](https://css-tricks.com/centering-css-complete-guide/)

* [Positioning of callout and centering content [2]](https://damianism.github.io/custom_pc/)

* [Adding shadow cover to background image](https://stackoverflow.com/a/24084708)

* [Adding border and box shadow to about-us images](https://www.w3schools.com/css/css3_images.asp)

* [For single page scroll effect](https://www.turnwall.com/articles/adding-single-page-scrolling-navigation-to-your-site/)

* [Nav link hover effect](https://stackoverflow.com/a/9586632)


### Investment Information Sources ###

* [Value Investing](https://www.moneyunder30.com/value-investing/)

* [Diversification](https://www.investopedia.com/investing/importance-diversification/#:~:text=What%20Is%20Diversification%20in%20Investing,differently%20to%20the%20same%20event.)

* [Risk Arbitrage](https://www.investopedia.com/terms/r/riskarbitrage.asp)

### Image Sources ###

* [Investment Hero Image](https://www.pexels.com/photo/airport-bank-board-business-534216/)

* [Mohamed Ali, Staff Image](https://www.pexels.com/photo/smiling-black-businessman-in-suit-sitting-on-table-4668490/)

* [Sarah Huang, Staff Image](https://www.pexels.com/photo/woman-posing-937483/)

* [Mercy Nyong'o, Staff Image](https://www.pexels.com/photo/woman-wearing-gray-notch-lapel-suit-jacket-2381069/)

* [Peter Andersson, Staff Image](https://www.pexels.com/photo/man-wearing-white-dress-shirt-and-black-blazer-2182970/)


### Special Thanks ###
* My mentor and The Grandmaster Yoda himself, [Simen Daehlin](https://github.com/Eventyret), for guiding me along the way and helping me find my way when I got lost. For being understanding and patient with me. 
* [byIlsa](https://github.com/byIlsa) for her awesome, well-structured README that helped me to write mine.
* The Code Institute tutors and Slack community for their assistance and guidance.