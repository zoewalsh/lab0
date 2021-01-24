# Project 0

ENGO 551 - Adv. Topics on Geospatial Technologies

My personal webpage displays a photo of me, some information about me, contact information for email and linkedin, some lists of my interests, as well as some of my film photography work.

index.html - This is the home page of the site. It shows my name, a caption (Geomatics Engineering Student), a rectangle shape, and 4 bootstrap buttons for navigating from page to page. The button colour and text colour of the button changes as it is hovered over. The page you are on appears as a different button colour.

page1.html - This is the "About Me" page of the site. It contains my photo, a table with my education information, and a link to my linkedin page. The bootstrap navigation buttons are also at the top of the page under the title.

page2.html - This is my "Interests" page of the site. It contains 3 bootstrap columns for each category of my interests. Each category contains an unordered list. Below that, 3 more bootstrap columns each contain a photo and a caption. The bootstrap navigation buttons are also at the top of the page under the title.

page3.html - This is my "Photography" page of the site. It contains a small header description and 2 bootstrap columns below. Each of the bootstrap columns contains the name of the camera used as well as some of the photos taken on that camera. The bootstrap navigation buttons are also at the top of the page under the title.

styles.css - This is one of the style sheets for the site. It contains the @media query and other css selectors/properties. #id and .class selector are used here.

variables.scss - The sass file containing a use of inheritance (setting font) and a use of nesting (setting the colour for two different headings).

variables.css - variables.scss converted to css.

-Changes for mobile-

Through @media query - rectangle size on home page changes width, any h4 and h5 text gets smaller on all pages, photo on "About" page takes up a greater amount of the width of the page, table on "About" page changes to scroll.

Automatically changes with bootstrap - bootstrap buttons stack, bootstrap columns stack on "Interests" page
