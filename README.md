# bootstrap-samples

# 1.1 Objectives

· Identify the applications and benefits of Bootstrap

o Responsive Web Design (RWD), Disadvantages of sites without RWD, Mobile First design, Bootstrap 4, emulate devices in Chrome Browser

· Demonstrate bootstrap usage with starter template

o doctype, viewport meta tag and attributes, Bootstrap CDN

· Demonstrate RWD using Grid System

o Grid System, 12 columns, devices and corresponding prefix of bootstrap class, container, container-fluid, row, col

· Demonstrate creation of navigation bar

o navbar, navbar-expand-lg, navbar-dark, bg-dark, navbar-brand

## Login Page Layout for hTrack Application

Health tracking application hTrack requires a login web page. The left hand side of the application displays the features and benefits of the online application. Right hand side of the web page displays login form. For the sake of simplicity, the login form details are not included.

## Navigation Bar for hTrack

Include navigation bar for hTrack login page.

# 1.2 Objectives

· Demonstrate creation of navigation bar items

o navbar-nav, nav-item, nav-link

· Demonstrate collapsing navigation items

o navbar-toggler, navbar-toggler-icon, collapse, navbar-collapse, ml-auto

· Demonstrate troubleshooting UI issues using Chrome Developer Tools

o Element selection

1. using Inspect

2. selection tool in Developer Console

3. Hovering over the elements in the HTML code within the "Element" section of Developer Tool

o Applying Styles directly using Developer Tools

1. Add new style in the style window

2. Disable an existing style using the checkbox

3. Change value of an existing style

· Demonstrate using badge component

o badge, badge-primary

· Demonstrate using third party icons in web page design

o Google Material Icon, Content Delivery Network (CDN), include icons in web page

· Demonstrate displaying a list of items

o list-group, list-group-item

## Navigation Bar Items for hTrack

Include navigation bar items in the navigation bar created for hTrack login page.

## Hamburger menu for mobile devices 

The navigation menu items displayed in two lines. Consider a situation where there are more navigation items, which will make the display of navigation items clumsy. In mobile devices, the navigation items should collapse within a hamburger menu. Clicking on the hamburger menu should display the menu items. Change the previous HTML page completed to display hamburger menu in mobile devices.

## Changing styles directly in browser using Chrome Developer Tools

Change the style of "Benefit" heading in hTrack application using Chrome Developer Tools using the steps specified below:

· Open the hTrack login screen in the browser

· Open Chrome Developer Tools

· Select the heading “Benefits” using Chrome Developer Tools

· In developer tools, increase 20px padding on top of the heading “Benefits”

· Uncheck “font-weight” style to disable and observe the changes in "Benefits" heading

· Change the color of “Benefit” heading to blue color

## Create a badge for displaying rating

There is a need to display the rating of a product

## Create icons for navigation item

Include home icon adjacent to “Home” navigation item using Google Material Icon.

## Listing Items

Display list of events using List Group component in Bootstrap.

# 2.1 Objectives

· Demonstrate displaying a card with image, title and body

o card, card-title, card-body, card-text, change mouse cursor on hovering an icon

· Demonstrate displaying list of cards with RWD

o Display a list of cards using grid system and thus enabling RWD

## Design rating display for a product

For displaying a product in hTrack application, the product rating needs to be displayed. For displaying star, use the Google Material Icon.

## Design display of Price for a product

For displaying a product in hTrack application, the product price needs to be displayed. For displaying offer image, use the Google Material Icon

## Design Add to Cart and Favorite for a product

For displaying a product in hTrack application, each product needs to be displayed with Add to Cart and Add to Favorite options. For displaying heart symbol, use the Google Material Icon. On hovering over the “heart”, the mouse pointer should be displayed in red and the mouse cursor needs to be changed as pointing hand.

## Displaying a Product using Card

A product in hTrack application needs to be displayed using Card component. Use the various components built in the previous exercises to build this layout. Get the image from https://unsplash.com/ , which is a free stock image site. Search for keyword "product" and the below product can be found. NOTE: It is recommended not to download the file. Get the image URL from unsplash.com and include it in the src attribute of img tag.

## Display multiple Products using Cards

Display multiple products. Each row will have four products displayed. In mobile devices there will be only one product displayed in a row. For images get the image links from unsplash.com.

# 2.2 Objectives

· Demonstrate using third party date picker in web page

o gijgo, getting started, setting date format

· Demonstrate displaying form elements with RWD

o Develop form with textbox, password, drop down, date using gijgo, radio button and checkbox form-row, form-group, form-control, form-check, form-check-input, form-check-label, form-check-input

· Demonstrate customizing bootstrap styles

o Separate CSS file for customization, overriding the styles of Bootstrap

## Using Third Party Library for Date 

Create a text field for capturing date using a third party JavaScript library called Gijgo.

## Design form to edit employee details

To capture employee details create a form.

## Customize Bootstrap Styles 

For a new application to be developed the default primary buttons is expected to be in green color with sharp edges. Achieve this by defining a new CSS file overriding the .btn and .btn-primary styles.
