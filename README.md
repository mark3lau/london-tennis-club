# **LONDON TENNIS CLUB**

## <u>1. Introduction</u>
My first project with Code Institute was to create a static front-end site to present useful information to users using HTML and CSS. London Tennis Club is a site that looks to connect keen tennis players of all abilities, living in London, so that they can play tennis whenever and wherever suits them and make new friends and socialise. The site is targeted towards people who want to play tennis but are struggling to find players within their current social group that are free and available at the same time as them. The site also provides information on public tennis courts in North, East, South and West of London. 
<hr>

## <u>2. User Stories</u>
As a tennis player in London, I want to find tennis players of similar ability near me so that we can play tennis at a time and day that suits us both.
### **End user goal:** 
Find tennis players near me to play tennis at a time and day that suits us both.
### **End business goal:** 
To connect tennis players across London from different social circles to play tennis.

### **Acceptance criteria:**
Home page will include information on what the website is about.
A user cannot complete the form without completing all mandatory fields. 
Users are directed to an acknowledgement page after completing the form.
Information on tennis courts will include links to the website and a google map of the location.

### **Measurement of success:**
A Home page that explains to the user what the site is about in brief, clear steps.
A registration form that allows users to complete all mandatory fields and be directed to an acknowledgement page.
A tennis courts page that includes brief descriptions of the tennis court with a link to the website, contact information and a google map of the location.
A fully functioning fixed header and social media links in the footer that are fully responsive to medium and small screen widths.
<hr>

## <u>3. Features</u>

### **Header and Navigation bar**
A fixed header is featured on all three pages of the site, allowing the user to navigate with ease through links to the Home page, Join Us (registration form) page and the London Tennis Courts information page. There is an additional Home page link in the shape of a tennis ball in the top left hand corner of the page to provide further ease for the user to navigate back to the landing page, and to add to the general aesthetics of the site that is tennis related.

### **Landing page image**
The landing page image includes an aerial photo of a tennis court with two players playing tennis that stretches across the full width of the screen. There is also a cover text that overlays the image to describe in short the purpose of the site for the user.

### **How it Works section**
The How it Works section allows the user to see immediately how the site works and how it could benefit them in four easy steps. Icons and a background image have been included to add to the overall aesthetics of the page.

### **Footer**
Social media links to Facebook, Instagram, Twitter, YouTube and Linkedin have been included in the footer section of each page, and each link will open in a new tab to allow the user to stay on the site. The purpose of the social media links is to allow users to stay in touch and promote the site using social media.

### **Join Us page**
The Join Us page is to allow the user to sign up to the site and join the community of London tennis players. The form requires users to submit information including their full name, email address, date of birth, gender and tennis ability. This information will allow the site to contact users and pair them with players of similar ability. A reset button has been added to allow users to quickly reset the form if needed as there are several lines of information requried.

### **London Tennis Courts page**
This page shows useful information on public tennis courts available in North, East, South and West London. Information include a brief summary of the courts, the website link, an email address and the address and Google map of the location of the courts. 
<hr>

## <u>4. Future features</u>

### **Blog page**
For users to interact with each other more efficiently and discuss all things tennis from tennis courts, rackets, to professional matches and results being played around the world.

### **Photo/Gallery page**
A page for users to upload images of their matches and the friends they have played with.

### **Merchandise/shopping page**
To allow users to purchase new equipment and clothing from retailers and suppliers, and an additional feature allowing users to sell their old tennis racquets and equipment. These features will have the potential to allow the site to generate new revenue streams and provide a sustainability message to users. 
<hr>

## <u>5. Typography and color scheme</u>
I have chosen a green and orange colour scheme as well as a bold font. Both provide a vibrant, modern and friendly site that will hopefully appeal to users. The green is also a colour associated with the Wimbledon tennis championship in London, a Grand Slam event that is well known around the world.
<hr>

## <u>6. Wireframes</u>
Using Balsamiq a basic wireframe was created to outline what I wanted to achieve with the site, with the initial layout and information required for each page.
<hr>

## <u>7. Technology</u>
HTML and CSS.
<hr>

## <u>8. Testing</u>

   ### **Code validation**
   HTML and CSS. A few errors were found when the codes were put through the W3C and Jigsaw validators that were easily fixed, these include certain property values that were incorrect and/or irrelevant.
   
   ### **Test cases (user story based with screenshots)**

   Desktop

   Home page
   As the user is on the Home page, the user is shown a fixed header with a navigation bar, and a hero image that's stretched across the full width of the page with a cover text on top of the hero image. It's followed by a How it Works section describing the four steps of the process and a footer containing five social media links to Facebook, Instagram, Twitter, YouTube and LinkedIn. Hovering over each of these links, the icons will increase in size to show the user that it has been selected. Clicking each of these social media links will open the home page of the social media page on a separate page in a new tab. The footer links and actions apply to all four pages of the site.
   At the navigation bar in the top right corner, as the user hovers over the links, a solid green line will appear over the selected link. Clicking on the Join Us link will take the user to the Join Us page. 

   Join Us page
   On the Join Us page, the user is greeted with a registration form. When the user types in their information in the text boxes but clicks Join without giving an input in all boxes, an error message "Please fill out this field" will appear. An error message "Please select one of these options" will also appear if the user clicks Join and no selection has been given for the Gender and/or the Tennis Ability fields. In the Date of Birth field, clicking on the box to the right of the field will open up a calendar that allows the user to choose a date. If information has been added to the fields and the user clicks the Reset button, this will reset all fields to blank.

   Than You page
   Once the user has input information into all fields and clicks Join in the Join Us page, they will be taken to a Thank You page and presented with a text box confirming to the user that they have successfully registered. The fixed header and footer with social media links are located at the top and bottom of the page as per other pages. From here, clicking on the London Tennis Courts page will take the user to a new page.

   London Tennis Courts page
   On the Tennis Courts page, the user is presented with 4 sections with information on tennis courts in North, East, South and West London. Each section has a google map towards the right that is fully responsive with Zoom in and out options, and clickable options for Reviews, Directions and to view a larger map. Clicking any of these three options will open up the page in a new tab. Each section also has a website link which when clicked, will open the page in a new tab. Clicking on the tennis ball image in the top left of the page will take the user back to the Home page, this works for all four pages for the user.

   Mobile
   

   ### **Fixed bugs**

   How it Works icons. 
   
   Bug - The icons were positioned in the top right of the text box and not centered properly in line with the text, and I could not change the size of the icons to fit inside the text box.

   Solution - The first step was to change the position of the How it Works divs to position:relative. In order to target the size of the icons I used em values to the font-size property. The icons were also given a position:absolute property, and in order to center the icons I used a left: calc(50% - 26.25px) to ensure it was centered properly.

   ### **Unfixed bugs**
   There are no known unfixed bugs.
   
   ### **Supported screens and browsers**
   The site is fully supported for medium and small mobile phone screen widths of 950px and 390px. The images, texts, form, navigation bar and social media links have all been adjusted so that the user experience is unaffected for different screen sizes.
<hr>

## <u>9. Deployment</u>
   9.1 via gitpod
   9.2 via github pages
<hr>

## <u>10. Credits</u>

   ### **Content**
   The codes for the implementation of the cover text on the Home page and the background image in the How it Works section was taken from the Code Institute Love Running walkthrough project.
   The icons in the How it Works section on the Home page and the social media links in the footer were taken from Font Awesome.
   The information on Finsbury Park tennis courts in North London was taken from the [Finsbury Park tennis](www.finsburyparktennis.org.uk) website. The map of Finsbury Park tennis courts was taken from Google maps.
   The information on West Ham Park tennis in East London was taken from the [West Ham Park tennis](www.clubspark.lta.org.uk/westhampark) website. The map of West Ham Park tennis was taken from Google maps.
   The information on All Star tennis courts in Wandsworth Common in South London was taken from the [All Star tennis](www.allstartennis.co.uk) website. The map of the All Star tennis, Wandsworth Common was taken from Google maps.
   The information on Queen's Park tennis courts in West London was taken from the [Queen's Park tennis courts](www.clubspark.lta.org.uk/queensparktenniscourts) website. The map of Queen's Park tennis courts was taken from Google maps.
    
   ### **Media**
   The hero image, background image in the How it Works section and the background image in the Thank You page were all taken from the website [Pexels](www.pexels.com).
   The background image in the Join Us page was taken from the website [Pixabay](www.pixabay.com). 
   The tennis ball image in the header was taken from the website [Etsy](https://www.etsy.com/uk/listing/684097429/tennis-ball-drink-coasters-pack-of-4-or?gpla=1&gao=1&&utm_source=google&utm_medium=cpc&utm_campaign=shopping_uk_en_gb_-home_and_living&utm_custom1=_k_Cj0KCQjw-daUBhCIARIsALbkjSY-80gIThyKfdcO1jT3Q2T_PawCbWR_TQ6WMYfLkrJEnDFdvvlc3p8aAinHEALw_wcB_k_&utm_content=go_14821442085_125173007022_549119977872_aud-1184048147899:pla-303628061699_c__684097429engb_116041132&utm_custom2=14821442085&gclid=Cj0KCQjw-daUBhCIARIsALbkjSY-80gIThyKfdcO1jT3Q2T_PawCbWR_TQ6WMYfLkrJEnDFdvvlc3p8aAinHEALw_wcB).