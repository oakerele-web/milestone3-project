<img src="/static/images/responsive.png" style="margin: 0; width: 80%;"><br>

# Data Centric Development - Code Institute/O Akerele – Milestone3 Project 

***Preamble***<br>
This is my Milestone3 project. It is a **Jargon Dictionary** that is designed to accommodate different professions.<br>
The site is designed to allow registered members to contribute populate the dictionary. They are able to perform<br> 
the following operation in the dictionary: Create, Read, Update and Delete (CRUD operation).<br> 
Similarly, there is administrator priviledge who has the power to perform the CRUD operation and additionally, the<br> 
only one that could introduce a new category before registered members could begin to perform the CRUD operation on<br> 
the newly created category.<br>
Furthermore, it is noteworthy that this site is work-in-progress as there is still a lot of room for improvement. For<br>
example: password restriction, populating the Profile Page with User personal profile and word contributions.

# Table of Contents
1. [UX](#ux)
    - [Project Goal](#project-goal)
    - [User Goal](#user-goal)
    - [Developer Goal](#developer-goal)
    - [User Stories](#user-stories)
    - [Design Choices](#design-choices)
2. [Wireframe](#wireframe)
3. [Existing Features](#existing-features)
    - [Home Page](#home-page)
    - [All Words Page](#all-words-page)
    - [Log In Page](#login-page)
    - [Profile Page](#profile-page)
    - [New Word Page](#new-word-page)
    - [log Out Page](#logout-page)
    - [Manage Category Page](#manage-category-page)
4. [Features](#features)
    - [Existing Features](#existing-features)
    - [Features Left](#features-left)
5. [Technologies Used](#technologies-used)
6. [Testing](#testing)
7. [Deployment](#deployment)
8. [Credits](#credits)
    - [Content](#content)
    - [Media](#media)
    - [Acknowledgement](#acknowledgement)

# UX:
## Project Goal
The whole idea behind this project is to provide **Jargon Dictionary** where external users will be able to search for<br> 
words/meanings and particularly for the users to be able to contribute their own words and definitions to the dictionary.<br>
## User Goal
The User goal is to be able to lookup for jargons according to their profession and the meaning of such word. Also, the user<br>
will be able to populate the dictionary by adding new words and meanings.<br>
## Developer Goal
The Developer goal is mainly to collect good definitions of professional jargons which is to eventually be published into a<br> dictionary in form of a book.<br>
## User Stories
1. As a User I want to be able to search for a jargon and find the meaning to the word.
2. As a User, I want to be able to contribute my quota e.g. if I know a new jargon that is not already in the dictionary, I<br> 
want to be able to add it.
3. As a User, I want to be able to Edit/Update my contributions to the dictionary.<br>
4. As a User , I want to be able to Delete any of my contributions.
## Design Choices
Bearing in mind the three main purposes of design i.e. communication, aesthetics and functionality, I choose to use grey and light<br> grey with white background to build a beautiful and attractive user interface. Green, red, and light grey colors are used for the buttons.     

# Wireframe using Balsamiq:
* Sketching
* Drawings
* Features
* Design with Balsamiq

<a href="/workspace/milestone3-project/static/images/mobile sketch for home & allwords.png">Sketch1</a><br>
<a href="/workspace/milestone3-project/static/images/mobile wireframe for home & allwords.png">Wireframe1</a><br>
<a href="/workspace/milestone3-project/static/images/mobile sketch for login & register.png">Sketch2</a><br>
<a href="/workspace/milestone3-project/static/images/mobile wireframe for login & register.png">Wireframe2</a><br>
<a href="/workspace/milestone3-project/static/images/mobile sketch for profile &manage category1.png">Sketch3</a><br>
<a href="/workspace/milestone3-project/static/images/mobile wireframe for profile & manage category1.png">Wireframe3</a><br>

# Existing Features:
There are 7 key pages on this website:
* [Home Page](#home-page)
* [All Words Page](#all-words-page)
* [Log In Page](#login-page)
* [Profile Page](#profile-page)
* [New Word Page](#new-word-page)
* [Log Out Page](#logout-page)
* [Manage Category Page](manage-category-page)

Every page is designed to show the navbar displaying the name of the dictionary and the interactive pages at the top right. The mobile<br> phone is designed to display the pages in a collapsible manner because of the number of pages to be displayed, the minimum of which is<br> four and maximum of six and some pages have lengthy name e.g. Manage Category. In the middle are the sections that display the<br> 
message/information for the page.  The navbar was designed with the help of Materialize (materializecss.com).<br>

## Home page

The Home page is an introductory page for the **Jargon Dictionary.** It contains the navbar and only four pages viz: Home, All Words,<br> Log In and Register. The main page contains an introduction to what the the dictionary is all about. It defines Jargon and the types<br> of users which has been broken to Type 1 and Type 2.

## All Words Page

This page like the previous page displays the navbar. The main body is the container for all the words contained in the dictionary and<br> they are arranged in alphabetical order. This is the page where all the new words contributed to the dictionary are recorded. It is<br> designed to show the word with a drop down arrow by its side, it is an accordion element that expand when clicked on to show:<br>
1. word meaning,<br>
2. category that the jargon belong to and<br>
3. the name of the creator.<br>

## Log In



## Contact Us

This page has been linked to the bottom of the home page where the address, the phone number and the email<br> 
address of the gym can be located. 


# Features to implement

As earlier stated, the website  is a work-in-progress and can still be improved upon. In the future, potential members<br> 
will be able to register online to become members and those that just want to use the Gym's services without being<br> 
members will be able to book online for whatever services they want at the time they want it from the comfort of their<br> 
homes as against what obtains now (booking and paying over the phone and in the office).    

# Technologies Used

The following technologies were used to create the website:

* Gitpod full template - workspace
* Bootstrap 4.4.1 - used to simplify the structure and to make it responsive.
* FontAwesome 4.7.0 - accessed for social media icons.
* jquery 3.4.1 - used to reference Javascript modal
* Google Fonts - used to style the website fonts.
* Balsamiq - the tool used to create the wireframe.

# Testing

## Header

The header has a logo on the left-hand side and the menu bar at the right-hand side. The Menu contains the name and<br>  
a Font Awesome icon for each of the features. When a user hovers their mouse over the menu, it hovers up to show the<br> 
exact menu item that is to be opened for emphasis and the background color of ash. This has been manually tested and it<br> 
works all across the web pages. Any of the pages can be seen and navigated from every page. It has been tested and found<br> 
to be responsive. The header acts responsively across all resolutions too.
  
## Home Page 

The home page otherwise known as the landing page contains three sections viz: about us/picture of the front view of Fitness Always<br> 
gym; the opening hours and contact details. The about us is a catching statement about the gymnasium to attract new customers.<br>
It shared the row 50:50 with the front view photo of the gym. Section two is the opening hours of the gymnasium. It shows when the gym<br>
is opened in the morning and closed in the night from Monday to Friday. This was styled to be positioned in the center. Finally, the contact<br> 
session shows how the gym could be contacted either by post, telephone and/or email. The section is colored with gold after the menu<br> 
bar contact-us color and linked with the contact page i.e. when the contact page is clicked from the menu bar, it links a user to this contact<br> 
page and it does not matter which page the user is, once the contact page is clicked, it immediately directs the user to this section. This was<br> 
tested across all the devices and it works fine.

## Facilities Page

This page explains to potential customers what services are available in the gym. At the moment, only six services are available but as time<br> 
goes on, the gym will expand and add other services. The services are styled with Font Awesome Icons by the side of the title of each service.<br>
The test carried out on this page was to navigate to it from another page and it works fine. Also, it works nicely across all the devices: mobile<br> 
phone, iPad and desktop. 

## Gallery Page

When a user navigates to this page, it shows the different pictures of machines and tools available for use in the gymnasium. The pictures are<br> 
nicely padded to differentiate them from one another. It has been tested to show these pictures across all the devices and the page can be navigated<br> 
from other pages.
 
## Contact Us Page

This has been explained vividly in section 3 of the home page. When this page is clicked, it takes the user straight to that section of the home page<br>
and this has been tested and found to be true from all other pages.

## Footer

The footer contains just the social media i.e. Facebook; Linkedin; Instagram; Twitter and YouTube. It is designed to share a<br> 
light green color with the facilities menu and centered. It is also designed to be sticky. The social media are represented by<br> 
Font Awesome Icons which are also styled with hover effect when the mouse goes over the icons. This has been tested across all<br> 
the pages and it holds. 

## SPELLING & GRAMMAR

All Fitness Always Gym text content and this Readme file has been been tested for grammar and spelling mistakes through Grammarly.

## The code has been validated using:

#### W3C Mark-up Validation Service and
#### W3C CSS Validation Service

This site has met the objective of creating an online presence with minimalistic design and content, but providing enough<br> 
information and platform to enable fast contact.<br>
The website has been tested across multiple browsers (Chrome, Safari, Firefox) and different screen sizes<br> 
(Galaxy C5, various iPhones, Huawei, iPad, iPad Pro and laptops) to make sure it is responsive. Bootstrap has been used<br> 
to achieve this.<br>
All fonts, images and other attributes have been changed accordingly to fit different screen sizes. Media queries have<br>
been used to make them work.


# Deployment 

The site was developed using Gitpod full template - workspace to commit and push to GitHub.<br>
GitHub Pages is a static site hosting service that takes HTML, CSS, and JavaScript files straight<br>
 from a repository on GitHub, optionally runs the files through a build process, and publishes a website.

## The following steps can be taken to access my page from the GitHub repository. 

On Github navigate to my-first-milestone-project<br>
From the menu at the top click on settings<br>
Scroll down to the GitHub pages section<br>
Under Source section click on the dropdown menu and select Master Branch as your GitHub Pages publishing source.<br>
Select save.

## To Clone the Repository
Navigate to the Github remote repository: oakerele-web.github.io<br>
Click 'Clone or Download'.<br>
Copy the clone HTTPS or SSH by clicking on the copy button.<br>
Open Git Bash.<br>
Change the current working directory to the location where you want the cloned directory to be made.<br>
Type git clone, and then paste the URL you copied.<br>
Press Enter. Your local clone will be created.<br>

***The URL for this project is as follows:***

https://oakerele-web.github.io/My-first-milestone-project/


# Credits 

## Content 

All the text contents in  this project are original because they are written by me.  

## Media 

All icons are from the Bootstrap website including the styling while the font styling is from Font Awesome website.<br> 
The Logo was formed and designed by me through Placeit.org using the fake name formed for the gym.<br>
Pictures used in the gallery page and the home page were copied from existing websites of gyms on the internet<br>

## Acknowledgments 

The Codeinstitute Resume project by Matt Rudge is what inspired this project and I chose this project from a list of<br>
other proposed projects by the Institute.<br>
Special thanks to Maranatha Ilesanmi - my course mentor - first for his objective view of the project at the selection<br> 
stage then assisting me with applications for my Wireframe/Mockups and finally this Milestone 1 project which he has helped<br> 
me a lot to review, re-structure and suggested solutions to my pertinent questions. I also thank Claire of the Student Care<br> 
department for her support and understanding when I needed adjustment to my calendar. I am also grateful to all our colleagues<br>
in Slack, thank you all.   

## Disclaimer 

*The content of this website is for educational purposes only.*
