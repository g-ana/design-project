# design-project
> initial prototype with fixed interactions for an online shopping web application 

An initial version of a prototype for an online shopping application made with *Figma*, a tool for developing interaction designs, is available on this [link](https://www.figma.com/design/Y1L9pPHhVuViYcMEvOztvQ/Design-project). Due to the restrictions of the Figma Free plan, the prototype includes limited fixed interactions. Product design and the design of user-centric application interfaces are incremental processes, so additional pages and functionalities are planned for the next iteration. The project comprises `9` pages, `2` frames, `2` sections, and `8` flows. 

###### header
1. The **Header** section is represented with a *main menu of navigation items*, including links to the other pages, where each of the items is created as a *group* of a medium-sized icon from the *system library of simple icons* and appropriate textual label, such as ***Home***, ***About us***, ***Contact***, ***Reviews***, ***Shipping***, ***Register***, ***Login***, and others. Color and size may be configurable to changes to different component states, for instance, *hover* and *active*. 

![Header section](https://github.com/user-attachments/assets/0ea4527e-f8fa-4090-8f00-93bea13588c5)

###### footer
2. The **Footer** section consists of *navigation buttons*, *groups* of an icon, and a textual label, intended to represent links to social media profiles, such as *YouTube*, *Twitter*, *Facebook*, and *Instagram*, and a *stats card*, a *group* of an icon and a textual description, containing information about the total number of followers.

![Footer section](https://github.com/user-attachments/assets/dabda079-4ee3-4d9a-8776-fb2e1981f701)

###### home page
3. The **Home** page consists of a *hero section*, an *image gallery*, and a *FAQ section*.
   * The *hero section* has a background color gradient, and contains a heading, a subheading, the `Get to know us` button, a link to the *About us* page, utilizing the *help* icon, the `View our product catalog` button, a link to the *Product catalog* page, utilizing the *list* icon.
   * The *image gallery* section is represented with `2` image placeholders.
   * The *FAQ section* contains a heading, a subheading utilizing the *stroked* text effect, and an accordion for the questions and answers, using the appropriate *chevron* icon, *down* for a closed item when the answer is hidden, or *up* for an open item when the answer is shown.

![Home page](https://github.com/user-attachments/assets/df424423-da36-4656-9ba9-e5f0fcdd1b52)

###### about us page
4. The **About us** page is designed as a *blog* with several *posts*, that can be used for product categories, events, and news. It consists of a *card grid content list*, where each *post* is a *card* containing a heading, a description, an image, and a `Learn more` button, intended as a link to a more detailed view, utilizing the *arrow-up-right* icon.

![About us page](https://github.com/user-attachments/assets/3408ea85-5327-49a1-9378-9b1e94ec8f79)

###### product item page
5. The **Product item** page is a detailed view of a product, displaying its name, price, description, and image. It also contains an `Add to cart` button, utilizing the *shopping-cart* icon, dropdown lists, to select a product color and size from the options, and a tag to indicate if the product is available (whether it is *in stock* or *out of stock*). In the top left of the product image, is a *heart* icon - a button for users to add the product to a wishlist. Additionally, the page might show some user comments related to the product. 

![Product item page](https://github.com/user-attachments/assets/6a5de47e-fd61-4faf-b6c9-82a7d0c9b37d)

###### reviews page
6. The **Reviews** page consists of a *newsletter subscription form*, *list of subscribers*, and *latest reviews*.
   * The *newsletter subscription form* contains an input field for e-mail address, and a `Submit` button. There is an example value, set as an input placeholder text.
   * The *list of subscribers* is an *avatar group*, where each avatar is an image of a subscriber in a *circle* shape.
   * The *latest reviews* is a *card grid* containing a list of reviews, where each review is a *card* containing a title, a textual description, the reviewer's name, and the date when the review was posted. It also includes an *avatar* of the reviewer, and product *rating* - a *group* of `5` icons *star*.

![Reviews page](https://github.com/user-attachments/assets/ada076ce-7093-4473-a711-dbc8e55742e6)

###### contact page
7. The **Contact** page consists of a *contact form*. The *contact form* contains input fields for the name, surname, and e-mail address of the user, a textbox field for a message, and a `Submit` button, utilizing the *send* icon - for sending the message. For each input field, there is a label text, a description - used as an input hint, a value - used as a placeholder text, and validation error messages, for example about a required field, content that cannot be empty, and invalid input format.

![Contact page](https://github.com/user-attachments/assets/96920e80-68b7-4813-9595-ecb3bc8c06d4)

###### shipping page
8. The **Shipping** page consists of a *shipping form*, intended to inform the users about the maximum number of days to receive an ordered product. This form contains an input field for the full name of the user, a textbox for a delivery note, a checkbox field for the users to accept that they have read the terms and conditions, a dropdown list to select a delivery location from the options, and a `Save shipping information` button, utilizing the *truck* icon.

![Shipping page](https://github.com/user-attachments/assets/93fc8fb5-e9ea-4ed6-a026-11b686351d66)

###### register page
9. The **Register** page consists of a *register form*. The *register form* contains input fields for an e-mail address and a password for the user, a checkbox to select if they want to receive e-mails with personalized offers and special discounts, and a `Register` button, utilizing the *user-plus* icon.

![Register page](https://github.com/user-attachments/assets/4606e3c9-8d49-4f5c-97ea-5686a2da1709)

###### login and reset password
10. The **Login** page consists of `2` frames, a *login* frame, and a *reset password* frame.
    * The *login form* contains input fields for the e-mail address and password (with a minimum and maximum length validation), a `Remember me` checkbox for keeping the user signed in, a `Sign in` button, utilizing the *login* icon, and a `Forgot password` link, navigating to the *reset password form*. The *reset password form* opens in *overlay* mode, as a modal dialog. 
    * The *reset password form* contains an input field for an e-mail address, to send a link for resetting the password, a `Reset password` button, utilizing the *repeat* icon, and a `Cancel` button, utilizing the *x-circle* icon. Clicking on the `Reset password` button confirms the e-mail address for the reset action link, and clicking on the `Cancel` button closes the form, returning to the *login form*. 

![Login and Reset password frames](https://github.com/user-attachments/assets/9f4e607a-6dd9-4dbd-8a36-19b822c198ef)

###### product catalog page
11. The **Product catalog** page consists of a *search form*, *sorting menu*, *filtering menu*, and *product results*.
    * The *search form* contains a product search input field, using an appropriate icon and a value for placeholder text.
    * The *sorting menu* contains several *button toggles*, so users can select one sorting option, for example, ordered by the best product rating, newest items first, ordered by price ascending, or by price descending. Each button is a group of icon and a textual label, the button icon should be visible only in active state, and a different color should highlight the selected option.
    * The *filtering menu* contains a *filter* icon, a *filter keywords* part, using a group of tags, a *slider input field* for setting a price range filter (including a slider, label, output, description, knob start, and knob end), and *checkbox groups* to filter the product results by the selected colors, sizes, or other options.
    * The *product results* contains a *card grid* of *product info cards* with the *drop shadow* effect, where each card shows info for a results item, including the product name, price, description, and image. 

![Product catalog page](https://github.com/user-attachments/assets/92c74d8b-8eab-47b0-a2ce-fe9d3556ac7b)
