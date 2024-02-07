# CAMel Tools Presentation

**Introduction**

This project relies on HTML and JavaScript designed for a CAMel Tools presentation.
The website includes sections for About, Home, and Youtube, along with a navigation bar.
Users can navigate through the sections, view a slideshow, and log in to the website.

**JavaScript features used:**

- Regex: The regular expressions used in this code are the same as those used in the partial exam.

- Event Handling:
  - onclick
  - keyCode 13 (used only in the login modal)

- Data Storage:
  - sessionStorage.setItem 
  - sessionStorage.getItem

- Conditional Statements and Loops:
  - if statements
  - for loops

- DOM Manipulation:
  - getElementById 
  - getElementByClass

- Styling Manipulation:
  - .style

- Timed Execution:
  - setInterval

- User Interface Interaction:
  - showSlides
  - plusSlides
  - currentSlide

- Section Display Control:
  - showSection

- Login Functionality:
  - checkLoginStatus
  - login
  - showLoginModal
  - closeLoginModal

- Custom Alert:
  - showCustomAlert
  - closeCustomAlert


**Features:**

- Navigation Bar: The top bar provides links to different sections of the presentation - About, Home, and Youtube.

- Slide Show: The home section includes a slideshow featuring different images. Users can navigate through slides using the "Previous" and "Next" buttons. Seamless navigation is facilitated through intuitive "Next" and "Previous" buttons, intelligently designed to elegantly fade out when reaching the beginning or end of the slides, ensuring a polished and distraction-free viewing experience.

- Clock: The website displays a real-time clock at the top right corner.

- Login Modal: Users are prompted to log in upon loading the page. The login modal requires a valid email and password, dismissing the "Login Modal" is not possible.

- Custom Alert: A custom alert is displayed for login feedback and other messages.

- Logged-In as: It will show the username of the logged-in user

