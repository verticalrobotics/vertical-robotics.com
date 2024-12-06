USING THE MAILCHIMP FORM:

To use the mailchimp form you need a mailchimp url. To get the mailchimp url, login to 
your mailchimp account, click the Audience menu and select signup forms. Then choose 
embedded forms and select unstyled form. In the generated form code get the value of 
the form ACTION attribute and use it as your mailchimp url. Open the main.js file located
in the template's "js" folder and look for this line of code: 

const cfg = {

    // MailChimp URL
    mailChimpURL : 'https://facebook.us1.list-manage.com/subscribe/post?u={u}&amp;id={id}' 

};


Replace the value of mailChimpURL with your mailchimp url.


-------------------------------------------------------------------------------------------------------


SOURCES AND CREDITS:

We've used the following resources as listed.

Template:
 - Booth (https://styleshout.com/free-templates/booth/)

Fonts:
 - Inter Font (https://fonts.google.com/specimen/Inter)
 - Heebo Font (https://fonts.google.com/specimen/Heebo)

Icons:
 - Boxicons (https://boxicons.com/)

Stock Photos and Graphics:
 - Unsplash.com (https://unsplash.com/)
 - Pexels.com (https://www.pexels.com/)
 
Javascript Files:
 - Swiper (https://swiperjs.com/)
 - MoveTo.js (https://github.com/hsnaydd/moveTo)
 - Prism.js (https://prismjs.com/)
 - Basic Lightbox (https://basiclightbox.electerious.com/)
