# Cook Club
The Cook Club is a page for kids looking for a fun cooking club aged between 7-18. Cook Club offers fun cooking classes for young adults to help them improve their cooking skills.  On this website, users will be able to find the information that they need about the Cook Club such as meeting times, age groups, package offers, photos of kids cooking and sign-up form.

![Screenshot 2024-03-30 104616](https://github.com/stef-von-d/cook-club/assets/159139306/49671e63-96eb-4fe0-8848-c94b0e630970)




## Features
### 	Navigation Menu
*	Feature at the top of the page, the navigation shows the club’s name in the left corner: Cook Club which links to the top of the page.
*	The other navigation links are to the right: ABOUT US, GALLERY and SIGN UP which links to different pages.
*	The navigation clearly tells the user the name of the club and website and makes the sections easy to read.
  ![Screenshot 2024-03-25 121701](https://github.com/stef-von-d/cook-club/assets/159139306/acaa9eee-ca17-496c-b4ff-33aed5b587d5)
  
###     Header
*	The header explains the club is for kids and young adults aged between 7-18. 
*	This section provides the user with clear information about the site and who is the club for.
*	On the right hand size in the header it is a picture with kids cooking. 
![Screenshot 2024-03-25 121815](https://github.com/stef-von-d/cook-club/assets/159139306/0c586486-16ce-4d3a-b115-786cbb34194e)

###    About Us
*	The About Us section offers a better insight into the club concept and what is included in the package when a kid joins the Cook Club.
*	In this section, users will be able to find a table with the day, time and age information.
  
![Screenshot 2024-03-25 190910](https://github.com/stef-von-d/cook-club/assets/159139306/e352f582-b36c-45b6-b287-2ef0172d1e18)

### 	Footer
 * It contains the contact details and social media links. The footer gives the users the ability to find and contact the Cook Club if they want. 
 * The footer encourages users to get in touch and provides a phone number, email address, and street address where they can be found.
 * Also, in the footer are social media icons so users can find the Cook Club on Facebook, Instagram and Twitter.  

![Screenshot 2024-03-25 191530](https://github.com/stef-von-d/cook-club/assets/159139306/02853d45-d02d-49f4-9e1d-53092db3f3ad)

### Favicon
* The favicon provides an image in the the tabs header to allow the user to easily identify the website if they have multiple tabs open ![Screenshot 2024-05-25 074018](https://github.com/stef-von-d/love-running/assets/159139306/a7e64e48-4748-445f-8e3f-98d33851b01a)
  
* Favicon taken from [Love Math Project](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LM101+3/courseware/2d651bf3f23e48aeb9b9218871912b2e/04d7bdb98119413991e2a31e9a291970/?child=first)

### 404 Page
* A 404 page will be implemented and will display if a user navigates to a broken link.
* The 404 page will allow the user to easily navigate back to the main website if they direct to a broken link / missing page, without the need of the browsers back button.

### Landing Page
* The landing page has an image with kids cooking along with brief information about the site giving the user an idea what the website is about.
  
![Screenshot 2024-05-25 075537](https://github.com/stef-von-d/love-running/assets/159139306/387fab43-3e5e-4da0-94cf-007fcf128db9)

 
### 	Gallery
*	The Gallery section shows pictures of the kids cooking with different age groups. 
*	This will allow website’s users to see a little insight of how it is like to be part of the Cook Club.
*	The gallery will be fully responsive on all devices and allows the user to filter by categories provided in a sub navigation.

![Screenshot 2024-03-30 103921](https://github.com/stef-von-d/cook-club/assets/159139306/09e8dafb-3a58-414e-b15e-059a319d87b3)

### Existing features
* Responsive design
* Resposive gallery
* Sign Up Form

### Fetures Left to Implement 
* Implementing filtering at the gallery page
* Animate the galley page

### 	Sign Up  
*	The signup section has a form to collect details for the user so user can sign up for the Cook Club.
*	The form collects the user’s name and email address.
*	The sign up form is important because through this method the users can sign up and join the Cook Club.
![Screenshot 2024-03-25 122354](https://github.com/stef-von-d/cook-club/assets/159139306/71a69e60-9931-4f1f-8e40-6def74af8677) 


## Technologies 
#### HTML
* The structure of the Website was developed using HTML as the main language.
#### CSS
* The Website was styled using CSS.
#### GitHub
*	Source code is hosted on GitHub and deployed using Git Pages.
#### Git
*	Used to commit and push code during development of the project.

#### Font Awesome
*	The social media icons were taken from [Font Awesome](https://fontawesome.com/)
#### Pexels 
* The images used in the Cook Club project were taken from [Pexels](https://www.pexels.com/)

  


## 	Testing 
### Responsiveness 
All pages were tested to ensure that responsive according to the W3c Web Accessibility on Chrome and Firefox browsers. 
Steps to test:
1.	Open browser and navigate to Cook Club 
2.	Open the developer tools (right click and inspect)
3.	Set to responsive and decrease width to 320px
4.	Set the zoom to 50%
5.	Click and drag the responsive window to maximum width

Expected:
Website is responsive on all screen sizes and no images are pixelated or stretched. No horizontal scroll is present. No elements overlap.<br>

Actual:
A few pictures size in the gallery have been changed to fit the responsiveness. As a result, the quality of some picture has changed. This issue is mentioned in bugs. 

### Accessibility

Manual accessibility testing was performed using Lighthouse. 	I confirm that the colors and fonts are easy to read and accessible by running it through lighthouse in devtools. 

![Screenshot 2024-03-25 124703](https://github.com/stef-von-d/cook-club/assets/159139306/4de9e9e6-01d9-4213-9d7d-db854c009200)




## Functional testing 
### Navigation links

Testing was performed to ensure all navigation links on the respective pages, navigated to the correct pages as per design. This was done by clicking on the navigation links on each page. 

| Navigation Link | Page to load |
| -----------     | -----------  |
| Home            | Index.html   |
| Gallery         | Gallery.html |
|Sign Up          |Signup.html   |


### Sign Up form testing

The sign-up form was tested to ensure it functioned as expected when correct data was input and when incorrect data was input. The following scenarios were covered. 

**Scenario One – Correct Inputs**
<br>
Steps to test: 
1.	Navigate to [Cook Club-Sign Up Form](https://8000-stef-von-d-cook-club-14jaf6j3a3.us1.codeanyapp.com/signup.html)
2.	Add the following data: 
* First Name: Tom
* Last Name: Smith
* Email: Tom.smith@gmail.com

3.	Click Join Now!
4.	User should be redirected to signup.html confirmation page. 

Expected:
Form submits with no warnings or errors and user is redirected to contact.html confirmation page. 
<br>
Actual:
Website behaved as expected with no errors or warnings.

<br>


**Scenario Two - Missing Required Field First Name**
<br>
Steps to test:
1.	Navigate to [Cook Club- Sign Up Form](https://8000-stef-von-d-cook-club-14jaf6j3a3.us1.codeanyapp.com/signup.html)
2.	Scroll down to the form and input the following data:
* First Name:
* Last Name: Tom
* Email: tom.smith@gmail.com 
3.	Click Join Now!
  
Expected:
The form does not submit and an Error is displayed to tell the user that the field is required. 
<br>

Actual:
Website is displaying a message letting the user know that a field was not filled. 

<br>

**Scenario Three - Missing Required Field Last Name**
<br>
Steps to test:
1.	Navigate to [Cook Club- Sign Up Form](https://8000-stef-von-d-cook-club-14jaf6j3a3.us1.codeanyapp.com/signup.html)
2.	Scroll down to the form and input the following data:
    * First Name: Tom
    * Last Name:
    * Email: tom.smith@gmail.com 
3.	Click Join Now!

Expected:
The form does not submit and an Error is displayed to tell the user that the field is required.
<br>
Actual:
Website is displaying a message letting the user know that a field was not filled. 
 <br>


**Scenario Four - Missing Required Field Email**
<br>
Steps to test:
1.	Navigate to [Cook Club- Sign UP Form](https://8000-stef-von-d-cook-club-14jaf6j3a3.us1.codeanyapp.com/signup.html)
2.	Scroll down to the form and input the following data:
* First Name: Tom
* Last Name: Smith
* Email:
3.	Click Join Now!
  
Expected:
The form does not submit and an Error is displayed to tell the user that the field is required.
<br>
Actual:
Website is displaying a message letting the user know that a field was not filled.

<br>

**Scenario Five - Incorrect email format**
<br>
Steps to test:
1.	Navigate to [Cook Club- Sign Up Form](https://8000-stef-von-d-cook-club-14jaf6j3a3.us1.codeanyapp.com/signup.html)
2.	Scroll down to the form and input the following data:
	* First Name:Tom
	* Last Name: Smith
	* Email: tom.smithgmail.com
3.	Click Join Now

Expected:
The form does not submit and an Error is displayed to tell the user that a valid email is required and the format it should be in.
<br>
Actual:
The website is informing the user that “@” is missing.
<br>


### Footer Social Media Icons/Links
Testing was performed to ensured that each social media icon opened in a new tab. Each item opened a new tab when clicked as expected.


## 	Validator Testing 

### HTML
*	No errors were returned when passing through the official [W3C validator](https://validator.w3.org/) .

![Screenshot 2024-05-25 081348](https://github.com/stef-von-d/love-running/assets/159139306/931df64f-f701-445b-bc57-cfab8fc5aa81)


 ###  CSS
*	No error found when returning through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/) .




## 	Deployment 

The site was deployed on GitHub pages. The deploy steps are:
*	In the GitHub repository, navigate to the Settings tab.
*	From the source section drop-down menu, select the Master Branch.
*	Once the master branch has been selected, the page provided the link to the complete website.
 

## Credits 


### Content
 *    The code to make the social media links was taken from the Code Institute Love Running Project. 
 *    The code to make the navigation bar were inspired by the YouTube tutorial [Responsive Website Landing Page Design](https://www.youtube.com/watch?v=JYWitDwHhxE&t=443s) and Code Institute Love Running Project. 


