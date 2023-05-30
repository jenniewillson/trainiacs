# Trainiacs testing record

## Table of contents

- [Validation Testing](#validation-testing)
  * [CSS Validation](#css-validation)
* [HTML Validation](#html-validation)
- [Trainiacs testing record](#trainiacs-testing-record)
  - [Table of contents](#table-of-contents)
  - [Validation Testing](#validation-testing)
    - [CSS Validation](#css-validation)
    - [HTML Validation](#html-validation)
      - [index.html](#indexhtml)
      - [modern.html](#modernhtml)
      - [diesel.html](#dieselhtml)
      - [steam.html](#steamhtml)
      - [gallery.html](#galleryhtml)
      - [contact.html](#contacthtml)
      - [signedup.html](#signeduphtml)
      - [404.html](#404html)
  - [Compatibility and Responsive Testing](#compatibility-and-responsive-testing)
  - [Manual Testing](#manual-testing)
    - [Mobile](#mobile)
    - [Tablet](#tablet)
    - [Desktop](#desktop)
    - [Simulation of other devices](#simulation-of-other-devices)
      - [iPhone XR](#iphone-xr)
      - [iPhone SE](#iphone-se)
      - [Samsung Galaxy s8](#samsung-galaxy-s8)
      - [Galaxy fold](#galaxy-fold)
      - [Samsung Galaxy s20 ultra](#samsung-galaxy-s20-ultra)
      - [iPad mini](#ipad-mini)
    - [User stories](#user-stories)
  - [Defect Tracking](#defect-tracking)
  - [Defects of Note](#defects-of-note)
      - [Of note due to length of time taken to resolve](#of-note-due-to-length-of-time-taken-to-resolve)
      - [Of note due to key learning points](#of-note-due-to-key-learning-points)
  - [Outstanding Defects](#outstanding-defects)
  - [Accessibility Testing](#accessibility-testing)
    - [Accessibility Audits](#accessibility-audits)
      - [Contrast checker](#contrast-checker)
      - [Lighthouse](#lighthouse)
        - [index.html](#indexhtml-1)
          - [Mobile](#mobile-1)
        - [Desktop](#desktop-1)
      - [modern.html](#modernhtml-1)
          - [Mobile](#mobile-2)
        - [Desktop](#desktop-2)
      - [diesel.html](#dieselhtml-1)
          - [Mobile](#mobile-3)
        - [Desktop](#desktop-3)
      - [steam.html](#steamhtml-1)
          - [Mobile](#mobile-4)
        - [Desktop](#desktop-4)
      - [gallery.html](#galleryhtml-1)
          - [Mobile](#mobile-5)
        - [Desktop](#desktop-5)
      - [contact.html](#contacthtml-1)
          - [Mobile](#mobile-6)
        - [Desktop](#desktop-6)
      - [SignedUp.html](#signeduphtml-1)
          - [Mobile](#mobile-7)
        - [Desktop](#desktop-7)
    - [Keyboard Navigation](#keyboard-navigation)
    - [Screen reader](#screen-reader)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


## Validation Testing

### CSS Validation

![image](https://github.com/jenniewillson/trainiacs/assets/127458925/8b303821-81d2-4423-9186-a40d19ecb51a)

### HTML Validation

It is highlighted here that there could be a better use of headings. I considered this but felt that with the website being quite simple and pages working well linearly, this was not a high requirement. It is, however, something I would consider for the future.

#### index.html
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/bed30507-6283-49fa-bbd3-822c5edaced9)

#### modern.html
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/41061766-e5a8-4cd6-8c77-0a8e1a929a27)

#### diesel.html
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/fdd390f2-7859-44ee-8c34-888a0fc4dbcb)

#### steam.html
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/f365d4a6-695d-4411-9c00-6620c3674c43)

#### gallery.html
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/79be62a8-a7f5-4513-884d-a1450c3d47c5)

#### contact.html
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/d0567a2f-747b-4770-9dba-fd70ab7aef98)

#### signedup.html
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/72bf7344-32a7-4f54-b53a-2124191ee5dd)

#### 404.html
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/eaad865a-1d34-4008-9641-90ea9766c56c)

## Compatibility and Responsive Testing

## Manual Testing

### Mobile

Tested on iPhone 13

|Requirement - *Home page*|Result|Comments|
|-------|-------|-------|
|Website loads|Pass|No delay|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|Testing showed the bottom theme image was part hidden behind the footer so this was corrected|
|Scroll works where appropriate|Pass|N/A|
|Logo Home link works|Pass|Re-loads Home screen|
|Dropdown menu appears on selecting hamburger icon|Pass|N/A|
|All menu links take user to correct screen|Pass|Note: returned to Home screen between each selection|
|Active menu item is correct|Pass|Home is underlined and heavier font|
|Theme picture links take user to correct theme pages|Pass|Note: returned to Home screen between each selection|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|N/A|
|Footer - Telephone link works|Pass|Brought up 'Call' option on phone with number|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page or relevant app|

|Requirement - *Modern page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Scroll works where appropriate|Pass|Able to scroll to see Gallery image|
|Logo Home link works|Pass|N/A|
|Dropdown menu appears on selecting hamburger icon|Pass|N/A|
|All menu links take user to correct screen|Pass|N/A|
|Active menu item is correct|Pass|N/A|
|Meetings are correct theme and all information visible|Pass|N/A|
|Map link takes user to Station Inn location on new tab|Pass|Link opened in default Maps app and took me straight to the location|
|Sign up section takes user to Contact us page/form|Pass|N/A|
|Gallery section takes user to Gallery page|Pass|N/A|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|N/A|
|Footer - Telephone link works|Pass|Brought up 'Call' option on phone with number|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page or relevant app|

|Requirement - *Diesel page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Scroll works where appropriate|Pass|Able to scroll to see Gallery image|
|Logo Home link works|Pass|N/A|
|Dropdown menu appears on selecting hamburger icon|Pass|N/A|
|All menu links take user to correct screen|Pass|N/A|
|Active menu item is correct|Pass|N/A|
|Meetings are correct theme and all information visible|Pass|N/A|
|Map link takes user to Station Inn location on new tab|Pass|Link opened in default Maps app and took me straight to the location|
|Sign up section takes user to Contact us page/form|Pass|N/A|
|Gallery section takes user to Gallery page|Pass|N/A|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|N/A|
|Footer - Telephone link works|Pass|Brought up 'Call' option on phone with number|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page or relevant app|

|Requirement - *Steam page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Scroll works where appropriate|Pass|Able to scroll to see Gallery image|
|Logo Home link works|Pass|N/A|
|Dropdown menu appears on selecting hamburger icon|Pass|N/A|
|All menu links take user to correct screen|Pass|N/A|
|Active menu item is correct|Pass|N/A|
|Meetings are correct theme and all information visible|Pass|N/A|
|Map link takes user to Station Inn location on new tab|Pass|Link opened in default Maps app and took me straight to the location|
|Sign up section takes user to Contact us page/form|Pass|N/A|
|Gallery section takes user to Gallery page|Pass|N/A|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|N/A|
|Footer - Telephone link works|Pass|Brought up 'Call' option on phone with number|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page or relevant app|

|Requirement - *Gallery page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Scroll works where appropriate|Pass|Able to scroll to see all images|
|Logo Home link works|Pass|N/A|
|Dropdown menu appears on selecting hamburger icon|Pass|N/A|
|All menu links take user to correct screen|Pass|N/A|
|Active menu item is correct|Pass|N/A|
|All images appear and show information on hover|Pass|Hover not usable on mobile but can hold thumb on a photo and description appears|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|N/A|
|Footer - Telephone link works|Pass|Brought up 'Call' option on phone with number|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page or relevant app|

|Requirement - *Contact page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Scroll works where appropriate|Pass|N/A|
|Logo Home link works|Pass|N/A|
|Dropdown menu appears on selecting hamburger icon|Pass|N/A|
|All menu links take user to correct screen|Pass|N/A|
|Active menu item is correct|Pass|N/A|
|Form shows correctly|Pass|N/A|
|Name is mandatory|Pass|Speech bubble shown to inform me to 'Fill out this field'|
|Email is mandatory and validated|Pass|Speech bubble shown to inform me to 'Fill out this field'|
|Any number of checkboxes can be checked|Pass|N/A|
|'Sign me up!' once form is correctly completed takes user to SignedUp page|Pass|N/A|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|Reloaded page|
|Footer - Telephone link works|Pass|Brought up 'Call' option on phone with number|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page or relevant app|

|Requirement - *SignedUp page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Scroll works where appropriate|Pass|N/A|
|Logo Home link works|Pass|N/A|
|Dropdown menu appears on selecting hamburger icon|Pass|N/A|
|All menu links take user to correct screen|Pass|N/A|
|Active menu item is correct|Pass|'Contact us' is shown as active|
|Home link in thank you section returns user to the home page|Pass|N/A|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|Reloaded page|
|Footer - Telephone link works|Pass|Brought up 'Call' option on phone with number|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page or relevant app|

|Requirement - *404 page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Logo Home link works|Pass|N/A|
|Clicking on text container returns user to Home|Pass|N/A|

### Tablet

Tested on iPad

|Requirement - *Home page*|Result|Comments|
|-------|-------|-------|
|Website loads|Pass|No delay|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Scroll works where appropriate|Pass|N/A|
|Logo Home link works|Pass|Re-loads Home screen|
|All menu links take user to correct screen|Pass|Note: returned to Home screen between each selection|
|Active menu item is correct|Pass|N/A|
|Theme picture links take user to correct theme pages|Pass|Note: returned to Home screen between each selection|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|N/A|
|Footer - Telephone link works|Pass|Brought up 'Call' option on phone with number|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page or relevant app|

|Requirement - *Modern page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Scroll works where appropriate|Pass|Able to scroll to see Gallery images|
|Logo Home link works|Pass|N/A|
|All menu links take user to correct screen|Pass|N/A|
|Active menu item is correct|Pass|N/A|
|Meetings are correct theme and all information visible|Pass|N/A|
|Map link takes user to Station Inn location on new tab|Pass|Link opened in default Maps app and took me straight to the location|
|Sign up section takes user to Contact us page/form|Pass|N/A|
|Gallery section takes user to Gallery page|Pass|N/A|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|N/A|
|Footer - Telephone link works|Pass|Brought up 'Call' options on iPad|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page or relevant app|


|Requirement - *Diesel page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Scroll works where appropriate|Pass|Able to scroll to see Gallery images|
|Logo Home link works|Pass|N/A|
|All menu links take user to correct screen|Pass|N/A|
|Active menu item is correct|Pass|N/A|
|Meetings are correct theme and all information visible|Pass|N/A|
|Map link takes user to Station Inn location on new tab|Pass|Link opened in default Maps app and took me straight to the location|
|Sign up section takes user to Contact us page/form|Pass|N/A|
|Gallery section takes user to Gallery page|Pass|N/A|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|N/A|
|Footer - Telephone link works|Pass|Brought up 'Call' options on iPad|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page or relevant app|

|Requirement - *Steam page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Scroll works where appropriate|Pass|Able to scroll to see Gallery images|
|Logo Home link works|Pass|N/A|
|All menu links take user to correct screen|Pass|N/A|
|Active menu item is correct|Pass|N/A|
|Meetings are correct theme and all information visible|Pass|N/A|
|Map link takes user to Station Inn location on new tab|Pass|Link opened in default Maps app and took me straight to the location|
|Sign up section takes user to Contact us page/form|Pass|N/A|
|Gallery section takes user to Gallery page|Pass|N/A|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|N/A|
|Footer - Telephone link works|Pass|Brought up 'Call' options on iPad|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page or relevant app|

|Requirement - *Gallery page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Scroll works where appropriate|Pass|Able to scroll to see all images|
|Logo Home link works|Pass|N/A|
|All menu links take user to correct screen|Pass|N/A|
|Active menu item is correct|Pass|N/A|
|All images appear and show information on hover|Pass|Hover not usable on iPad but can hold thumb on a photo and description appears|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|N/A|
|Footer - Telephone link works|Pass|Brought up 'Call' options on iPad|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page or relevant app|

|Requirement - *Contact page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Scroll works where appropriate|Pass|N/A|
|Logo Home link works|Pass|N/A|
|All menu links take user to correct screen|Pass|N/A|
|Active menu item is correct|Pass|N/A|
|Form shows correctly|Pass|N/A|
|Name is mandatory|Pass|Speech bubble shown to inform me to 'Fill out this field'|
|Email is mandatory and validated|Pass|Speech bubble shown to inform me to 'Fill out this field'|
|Any number of checkboxes can be checked|Pass|N/A|
|'Sign me up!' once form is correctly completed takes user to SignedUp page|Pass|N/A|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|Reloaded page|
|Footer - Telephone link works|Pass|Brought up 'Call' options on iPad|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page or relevant app|

|Requirement - *SignedUp page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|Testing showed the bottom theme image was part hidden behind the footer so this was corrected|
|Scroll works where appropriate|Pass|N/A|
|Logo Home link works|Pass|N/A|
|All menu links take user to correct screen|Pass|N/A|
|Active menu item is correct|Pass|'Contact us' is shown as active|
|Home link in thank you section returns user to the home page|Pass|N/A|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|Reloaded page|
|Footer - Telephone link works|Pass|Brought up 'Call' options on iPad|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page or relevant app|

|Requirement - *404 page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Logo Home link works|Pass|N/A|
|Clicking on text container returns user to Home|Pass|N/A|

### Desktop
|Requirement - *Home page*|Result|Comments|
|-------|-------|-------|
|Website loads|Pass|No delay|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Scroll works where appropriate|N/A|N/A|
|Logo Home link works|Pass|Re-loads Home screen|
|All menu links take user to correct screen|Pass|Note: returned to Home screen between each selection|
|Hover changes work for menu items and footer|Pass|Colour change and heavier|
|Active menu item is correct|Pass|N/A|
|Theme picture links take user to correct theme pages|Pass|Note: returned to Home screen between each selection|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|N/A|
|Footer - Telephone link works|Pass|N/A|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page|

|Requirement - *Modern page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Scroll works where appropriate|Pass|Able to scroll to see Gallery images|
|Logo Home link works|Pass|N/A|
|All menu links take user to correct screen|Pass|N/A|
|Hover changes work for menu items and footer|Pass|Colour change and heavier|
|Active menu item is correct|Pass|N/A|
|Meetings are correct theme and all information visible|Pass|N/A|
|Map link takes user to Station Inn location on new tab|Pass|Link opened in separate tab and took me straight to the location|
|Sign up section takes user to Contact us page/form|Pass|N/A|
|Gallery section takes user to Gallery page|Pass|N/A|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|N/A|
|Footer - Telephone link works|Pass|N/A|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page|

|Requirement - *Diesel page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Scroll works where appropriate|Pass|Able to scroll to see Gallery images|
|Logo Home link works|Pass|N/A|
|All menu links take user to correct screen|Pass|N/A|
|Hover changes work for menu items and footer|Pass|Colour change and heavier|
|Active menu item is correct|Pass|N/A|
|Meetings are correct theme and all information visible|Pass|N/A|
|Map link takes user to Station Inn location on new tab|Pass|Link opened in separate tab and took me straight to the location|
|Sign up section takes user to Contact us page/form|Pass|N/A|
|Gallery section takes user to Gallery page|Pass|N/A|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|N/A|
|Footer - Telephone link works|Pass|N/A|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page|

|Requirement - *Steam page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Scroll works where appropriate|Pass|Able to scroll to see Gallery images|
|Logo Home link works|Pass|N/A|
|All menu links take user to correct screen|Pass|N/A|
|Hover changes work for menu items and footer|Pass|Colour change and heavier|
|Active menu item is correct|Pass|N/A|
|Meetings are correct theme and all information visible|Pass|N/A|
|Map link takes user to Station Inn location on new tab|Pass|Link opened in separate tab and took me straight to the location|
|Sign up section takes user to Contact us page/form|Pass|N/A|
|Gallery section takes user to Gallery page|Pass|N/A|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|N/A|
|Footer - Telephone link works|Pass|N/A|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page|

|Requirement - *Gallery page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Scroll works where appropriate|Pass|Able to scroll to see all images|
|Logo Home link works|Pass|N/A|
|All menu links take user to correct screen|Pass|N/A|
|Active menu item is correct|Pass|N/A|
|All images appear and show information on hover|Pass|N/A|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|N/A|
|Footer - Telephone link works|Pass|N/A|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page|

|Requirement - *Contact page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Scroll works where appropriate|Pass|N/A|
|Logo Home link works|Pass|N/A|
|All menu links take user to correct screen|Pass|N/A|
|Active menu item is correct|Pass|N/A|
|Form shows correctly|Pass|N/A|
|Name is mandatory|Pass|Speech bubble shown to inform me to 'Please fill in this field'|
|Email is mandatory and validated|Pass|Speech bubble shown to inform me to 'Please fill in this field'|
|Any number of checkboxes can be checked|Pass|N/A|
|'Sign me up!' once form is correctly completed takes user to SignedUp page|Pass|N/A|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|Reloaded page|
|Footer - Telephone link works|Pass|N/A|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page|

|Requirement - *SignedUp page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Scroll works where appropriate|Pass|N/A|
|Logo Home link works|Pass|N/A|
|All menu links take user to correct screen|Pass|N/A|
|Active menu item is correct|Pass|'Contact us' is shown as active|
|Home link in thank you section returns user to the home page|Pass|N/A|
|Footer - 'Contact us' takes user to Contact us page/form|Pass|Reloaded page|
|Footer - Telephone link works|Pass|N/A|
|Footer - Email link works|Pass|Opened default mail app|
|Footer - Facebook, Twitter and Instagram links work|Pass|Opened separate web page|

|Requirement - *404 page*|Result|Comments|
|-------|-------|-------|
|Layout appearance is correct (check for visibility of text, layout, no overlaps)|Pass|N/A|
|Logo Home link works|Pass|N/A|
|Clicking on text container returns user to Home|Pass|N/A|

### Simulation of other devices

[Uswitch statistics](https://www.uswitch.com/mobiles/studies/mobile-statistics/) show that there has been a significant increase recently of the number of the older generation using smartphones, although desktop is still very popular. It is likely that a large proportion of the Trainiacs site users would be over 55 due to the popularity of Trainspotting as a hobby amongst that age range, as well as them being more available to spend time doing it, once retired.

The statistics show that in the UK the highest market share for smartphones is Apple, followed by Samsung, so it is important to check how the Trainiacs site renders on a range of these devices. Chrome developer tools were used to simulate these devices, and all pages were viewed and spot checking of functionality performed:

#### iPhone XR
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/a4c652f6-f9f7-4838-b108-4002a9db36c9)

#### iPhone SE
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/1db3d10c-0c53-4534-90b0-a5e69e7be6ed)

#### Samsung Galaxy s8
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/c313c414-4d9e-4049-9c77-69316a4ead05)

#### Galaxy fold
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/0a6fce53-22b4-43aa-80af-add9a975a124)

#### Samsung Galaxy s20 ultra
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/f10ca5f0-f175-4984-8d4c-e92ad0b352ce)

#### iPad mini
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/424b2909-10f9-4e7d-99c6-bca1473a83bb)

The most [commonly used Browsers in the UK](https://www.statista.com/statistics/421625/web-browser-market-share-in-the-united-kingdom-uk/#:~:text=The%20Chrome%20web%20browser%20from%20Google%20is%20the,the%208.53%20percent%20held%20by%20third%20place%20Edge.) are Chrome and Safari (on Apple devices), with Edge also having a significant market share. The Safari OS was used for the Tablet and Mobile testng above, and Chrome for the Desktop testing. Edge was also used during development and all functionality was confirmed to be working there also.

### User stories
|Story ID|Result|Comments|
|-------|-------|-------|
|US1|Pass|Future development to have a longer term calendar of events available, to be able to filter them on topic and to be able to have them in a database that dynamically updates|
|US2|Pass|Future development to be able to sign up for events with a number limit and ability to pay online|
|US3|Pass|In future consider adding a Q&A style page that users can post in and give answers and get email updates|
|US4|Pass|See above|
|US5|Pass|See above|
|US6|Pass|See above|
|US7|Pass|Future development to make at least one checkbox mandatory and to have a member page where you can update your mailing preferences|
|US8|De-scoped|This will require coding beyond the developer's current ability. However, at present this can be done via email, with the website administrator updating photos in the gallery manually. As the gallery is responsive to number and size of photos and screen, it will be a straightforward task to do this periodically|
|US9|Pass|N/A|
|US10|Pass|In future this would be connected to an endpoint and a database of details and preferences|
|US11|Pass?|Pass will be determined by whether I pass this milestone project!|
|US12|Pass|Yes, I have learnt a lot about how to code for screen readers, keyboard navigation, colour contrast etc.|

## Defect Tracking

- [Images not appearing](https://github.com/jenniewillson/trainiacs/issues/2#issue-1718216540)
- [Images disappeared after updated ](https://github.com/jenniewillson/trainiacs/issues/3#issue-1718308757)
- [Link not working for images on home page ](https://github.com/jenniewillson/trainiacs/issues/5#issue-1718324678)
- [HTML Validator errors](https://github.com/jenniewillson/trainiacs/issues/6#issue-1718326880)
- [Header background colour missing on some pages](https://github.com/jenniewillson/trainiacs/issues/8#issue-1718476485)
- [Nav-bar menu items left aligned](https://github.com/jenniewillson/trainiacs/issues/10)
- [Navbar border not reaching edges of page](https://github.com/jenniewillson/trainiacs/issues/11)

## Defects of Note

#### Of note due to length of time taken to resolve
- [Meeting items too far to the right](https://github.com/jenniewillson/trainiacs/issues/14)
- [Hamburger menu disappearing and wrapping](https://github.com/jenniewillson/trainiacs/issues/13)

#### Of note due to key learning points
- [Unmanageable css](https://github.com/jenniewillson/trainiacs/issues/4#issue-1718310163)
- [Social media links get 404 error](https://github.com/jenniewillson/trainiacs/issues/7#issue-1718469587)

## Outstanding Defects
- [Pictures are of a low quality](https://github.com/jenniewillson/trainiacs/issues/9)

## Accessibility Testing

### Accessibility Audits

#### Contrast checker
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/6271a7df-b2f1-4d1c-b73f-555a7e4d9e11)

![image](https://github.com/jenniewillson/trainiacs/assets/127458925/44101b4c-0d66-4b03-9e6b-d9191410ab36)

#### Lighthouse

##### index.html
###### Mobile
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/2e062400-3d72-40d7-b4a0-54c999de2727)
##### Desktop
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/1faf7f05-42fb-4ef5-aaf3-831caebcc1f4)

#### modern.html
###### Mobile
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/b0cf3c2b-208d-463e-ba7a-2c4306d09807)
##### Desktop
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/7c39ccef-863a-46e5-b436-0682d3d68ada)

*As below, Best Practice issue is image with incorrect aspect ratio - this relates to the track, which is not an issue as it appears as it is designed to - and XSS which is a learning point for the future for the developer:*

![image](https://github.com/jenniewillson/trainiacs/assets/127458925/9e3b03dc-c5e4-42ec-a2ac-ec710172e460)

#### diesel.html
###### Mobile
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/29d12331-c844-4b62-ac0b-1f242721c92b)
##### Desktop
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/0284a2be-3b9b-402a-8165-408413eceb95)

*Best practice issue is as per modern.html*

#### steam.html
###### Mobile
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/205d4abc-8f54-4a64-ae0b-5e0aa8bd4499)
##### Desktop
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/95acb52c-f491-4d9c-8662-b81e82f6fdf7)

*Best practice issue is as per modern.html*

#### gallery.html
###### Mobile
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/5705530b-2963-4e9d-823b-b03c9787319d)
##### Desktop
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/0b7cf51b-a67f-4aac-b674-9f410f9c9678)

#### contact.html
###### Mobile
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/6ff7a14c-7ade-46d3-9dd6-586adfbf7610)
##### Desktop
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/583480b7-762c-4c4d-b33a-3b9cd4610556)

#### SignedUp.html
###### Mobile
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/ef3fa772-7b42-4833-98f5-dfccd4af30ac)
##### Desktop
![image](https://github.com/jenniewillson/trainiacs/assets/127458925/07c27c4c-795b-49dd-bbce-5a270f7d16f7)


### Keyboard Navigation
![bandicam 2023-05-29 21-33-47-823](https://github.com/jenniewillson/trainiacs/assets/127458925/910d22a9-2b06-47e2-866a-750ca3fa137c)

### Screen reader
[Screen reader video](https://clipchamp.com/watch/pCEN24gf4NK)
