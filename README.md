# PORTFOLIO PROJECT - 1

# PETIT CLOTHING

## PURPOSE

Petit clothing is a website designed to encourage/invite people to give hand in hand to make world a better place. This website is designed to encourage people to share what they have especially clothes.
* [Here is a link to the final project](https://prakashoc507.github.io/Okaidi-Brussels/)

## INITIAL IDEA CONCEPT

My initial idea for the project was to develop a website so that we can make people aware of the utility of their used clothes. On a daily basis i see people throwing their used usable clothes. So, my website is for any person who is willing to give clothes rather than just dumping them.

The person can be of any gender or age. For this i have designed my website with appropriate effects and tools so that they can have easy access if they  want to make a donation. 

### Visitors Goal
* To easily understand the purpose of the site.
* To make site easy to read.
* Easy access to nav bar so that browser can easily navigate different pages.
* Interesting color combination and motivating content.

#  
#  
## CONTENTS

- [UX/UI](#uxui)
  * [USERSTORIES](#user-stories)
- [TESTING](#testing)
  * [LIGHTHOUSE](#lighthouse)
  * [ACCESSIBILITY](#accessibility)
- [SOLVED BUGS AND ERRORS](#solved-bugs-and-errors)
  * [UNSOLVED BUGS AND ERRORS](#unsolved-bugs-and-errors)
  * [FUNCTIONALITY](#functionality)
- [TECHNOLOGIES USED](#technologies-used)
  * [PROGRAMS USED](#programs-used)
- [DEPLOYMENT](#deployment)
  * [REMOTE](#remote-deployment)
  * [HOW TO FORK A REPOSITORY](#how-to-fork-a-repository)
  * [HOW TO CLONE A REPOSITORY](#how-to-clone-a-repository)
  * [HOW TO MAKE A LOCAL CLONE](#how-to-make-a-local-clone)

- [CREDITS](#credits-and-references)
  * [IMAGES AND INFORMATION](#images-and-information)
  * [CODE](#code)
- [ACKNOWLEDGEMENTS](#acknowledgements)

#  
#
# UX/UI
* This website was created to educate people to reuse or donate used usable clothes.
* The site should be simple to navigate.
* The site should be easy to read, there should not be any stretching or squeezing.

## Site Goals
* To show my intellegence in software develepment.
* To show my HTML and CSS skills.
* To provide user easy way to understand website and provide easy navigation links to navigate to different pages.
* To make site easily accessible.
## User Stories
* As a user, i want the website i am visiting to be attractive.
* As a user, i want the site i am visiting to be easy in navigating different pages.
* As a user, i want the site to be informative.
* As a user, i want to see the images or videos related to the title of site.


## Features of this site
* The site consists of 3 pages Home, About us and Signup.
* Each page are of same layout, Header, navbar,body with headings paragraphs, images and footer.
* Layout and content
 * The home page will have indroductory part with soothing background and with some motivational quotes, logo of the site and navigation links to different pages.
 * The about us page will have information about the petit clothing organization, its motos motivating lines and reasons behind the existance of organizatiion.
 * The donation page will have a form reauesting details of the donor like; name, last name, email address, freauencies of donation they want to make and description of donation box so that they can mention what clothes are they donating and for whom donation will be suitable for.
 * Hover effects on social media helps user to where which topic are they going to click on.
 * Solid border on the bottom of the link name will help user to identify user in which page of the site are they currenly in.
 * The difference between darker background and brigh content mentioned in page brings definate ease and pleasure to the user.
 * There are total of 7 images used for as background main image and clickable images.
 * All of the images used are used appropriately according to the size of the image and has not been compressed nor pushed past pixel in order to preven image quality.
 * The fonts used for my sites are lato, sans-serif and Ariel-Helvitaca. Font lato is importated from google fonts.
 * Icons for heading and social links are imported from font awesome.

 # Testing
 * As a user i want to understand the purpose of the site easily:
    * As you click home page you will be welcomed with very appealing and eye soothing transparent yellow background along with it, beautiful motivational will greet you.
* As a user, I want to easily understand the main purpose of the site`:
    * Upon loading the home page, you will be greeted with a motivational quote the sites context, "A man's true wealth is the good he does for the other people".
* As a user, I want to be able to navigate the site with an easy to see and read navbar:
    * This was fulfilled with clear to read wording, only four links with an underline for the page currently viewing
* As a user, I want the site to be attractive:
    * Made sure the visual effects, links, wording and images are appealing to the eye with the use of different shades of the same colour with brighter images and text
* As a user, I want to be able to learn something new.
* As a user, I want to see images related to the subject`
* I included a 'About US' link which includes multiple varied images.

## Lighthouse

* I ran each page live through Chrome Lighthouse and received the following results with above of 93.0% across the site

## SOLVED BUGS AND ERRORS

* I noticed a bug on each page that was identified as a lack of `max-width` on the `body` element, I have since set this to `1920px`
* Social links in about us page wer below the background, later i discovered that it was happening not nesting social links properly nested in a div. And was solved accordingly.
* Several times i was failing to position images at About Us page at center, later i solved it by setting margin to auto, and experimenting with width until the image positions into the center.  
* All of my three pages Home, About us and Done now were going up by 25% as we navigate the page, later it was found that, that was happening because of the container was using min-heigh of 100% so later it was solved by setting min-height if 100vh.
* Any duplicate or unused selectors, classes, id's and elements have been removed
* Any irrelevant space in between code has been removed


## UNSOLVED BUGS OR ERRORS
* The background color for paragraph element in Home page is overflowing.


## FUNCTIONALITY
* All links have been hovered over and clicked on to ensure accessibility.
* All Social media links work correctly and open on a new tab.
* All images load on each page as intended.

# TECHNOLOGIES USED

* [Google](https://www.google.com)
* [Facebook](https://www.facebook.com)
* [Instagram](https://www.instagram.com)
* [Twitter](https://www.twitter.com)

## PROGRAMS USED

* GIT
  * For version control, commiting and pushing to github.
* GITPOD
  * The IDE used to code this website.
* GITHUB
  * Used to store repositories, files and images pushed from gitpod.
* CHROME Developer tools.
  * For checking compatibilty, troubleshooting and editing code.
* FONTAWESOME
  * Used for the social media links in the footer of each page.

# DEPLOYMENT

## REMOTE DEPLOYMENT:
(Assuming you have already cloned or forked,)
* This site was deployed using GitHub Pages with the following the steps:

1. Click on the `Settings` icon at the top of page in the navigation bar
2. Scroll down until you see `Github Pages`
3. There will be a message box saying "Check it out here" Click on the link to take you to the next page.
4. Here you will be greated with a form, Choose the repository `Okiadi-Brussels`
5. Choose the branch in the drop down box, in this case `MAIN`
6. Choose the directory in the next drop down box, in this case `Root`
7. Then click `Save`
8. It may take a few moments for the site to publish, but once live, the box at the top of the page with the site name will turn green and have a `Green` tick to the left of the link to the live site
9. Another way to find the live site is to navigate to settings, on the left menu click on `pages` and this will get you to the same point.

* These commands were used for version control during project:

    * git add `example filename` - to add files before committing
    * git commit -m `"example message"` - to commit changes to the local repository
    * git push - to push all committed changes to the GitHub repository


1. If you have not already, login in to [GitHub](www.github.com) and go to https://github.com/prakashoc507/Okaidi-Brussels
2. In the top right corner, click `Fork`
3. The next page will be the forked version of https://github.com/prakashoc507/Okaidi-Brussels but in your own repository

## HOW TO CLONE A REPOSITORY:

If you need to make a clone of this repository:

1. Fork the repository https://github.com/prakashoc507/Okaidi-Brussels using the steps above
2. Above the file list, click `Code` (Usually green at the top right of the code window)
3. Choose if you want to clone using HTTPS, SSH or GitHub CLI, then click the copy button to the right
4. Open Git Bash
5. Change the directory to where you want your clone to go (your own github)
6. Type `git clone` and then paste the URL you copied in step 4
7. Press `Enter` to create your clone


## HOW TO MAKE A LOCAL CLONE

If you need to make a local clone:

1. If you have not already, login in to [GitHub](www.github.com) and go to https://github.com/prakashoc507/Okaidi-Brussels.
2. Under the repository name, above the list of files, click `Code`
3. Here you will have two options, `Clone` or `Download` the repository
4. You should close the repository using HTTPS, clicking on the icon to copy the link
5. At this point, you can launch the `Gitpod workspace` or choose your own directory
5. Open Git Bash
6. Change the current working directory to the new location of where you want the cloned directory to be
7. Type git clone and then paste the URL you copied in step 4
8. Press Enter, to create your local clone to your chosen directory

#

#

## CREDITS AND REFERENCES

### IMAGES AND INFORMATION
* Background images and images for about us page were found through different google resources, thanyou guys you made our life easy with such wonderful resource for knowledge. Most of the images were taken from here [Google](https://www.google.com/search?q=cloth+donation+images&rlz=1C1CHBF_nlBE1001BE1001&sxsrf=ALiCzsb_rzhSass9orhbicTj2y6R9dYq1A:1651198223532&tbm=isch&source=iu&ictx=1&vet=1&fir=A4_gps0vlI27iM%252Cj2qrAbDjw0BWyM%252C_%253BnZk3_PhacpkhpM%252ClvfRutP7Ihu3rM%252C_%253Bksm0urM9_CloZM%252ClvfRutP7Ihu3rM%252C_%253Bxi67TfMgry0gbM%252ClvfRutP7Ihu3rM%252C_%253BC5LxPUI89nVP5M%252CKNbxZWiA1aJlkM%252C_%253B8y8dWlzhwGtz_M%252CJiNmVVnvRXpd4M%252C_%253BrCWcJx-k0eX_QM%252CIM9yF2yQFjkpcM%252C_%253B55Sm_nmoLuoXKM%252ClvfRutP7Ihu3rM%252C_%253BiKPn15iXFA7i7M%252COfX7FnIcc3fCiM%252C_%253BqacaZNrvePsQ1M%252ClvfRutP7Ihu3rM%252C_%253BXZqOw9AMgrWA4M%252CftJBN7Fj2wdUgM%252C_%253BnxpeveXSQmxnGM%252CJiNmVVnvRXpd4M%252C_%253BwmhncmhkpYtp9M%252CcXt6g3HFRZw-oM%252C_%253B5SzmUcKLEPHQBM%252CcffZmH_UBpHQKM%252C_&usg=AI4_-kTDpl9yS57tC9wxUX_FlN2RgAKL0g&sa=X&ved=2ahUKEwiR1MTcmLj3AhXwgP0HHbWhD4wQ9QF6BAgEEAE#imgrc=sLw6WcYadtg7JM) 
* For different types of color combination this site is used  [Google](https://www.google.com/search?q=color+combination+for+white+background&rlz=1C1CHBF_nlBE1001BE1001&oq=color+pair+for+whit+bac&aqs=chrome.1.69i57j0i22i30l2j0i390.7959j0j7&sourceid=chrome&ie=UTF-8)

### Code

* Avinash on youtube [Youtube](https://www.youtube.com/c/EasyTutorialsVideo/videos) for his tutorial, some of the effects in my project are influenced by his idea. 

* Kevin Powell [Youtube](https://www.youtube.com/channel/UCJZv4d5rbIKd4QHMPkcABCw) 

* Code institue for Love Running Project.

* [W3Schools](https://www.w3schools.com/) for indepth coverage for HTML & CSS.


## ACKNOWLEDGEMENTS:

- Code institute for the Tutors on the course.
- My Mentor [Ben Kavanagh](https://github.com/BAK2K3) for pushing me and always asking me to surprise him with my codes.
- My Senior collegue/mentor [Chris williams](https://github.com/Chr15w1986). I really appreciate his effort to help me and would like to thank him for bringing me this far.
- My family for their support and patience.
- Everybody on Slack for tips, advice, quick fixes and kind words.

#### RETURN TO THE [TOP](#PETIT-CLOTHING)






















