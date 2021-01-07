# Inbound Case Work
 Inbound Case Work- Slider Button
# Slider Button Application 

##Intro 
You need to implement the following slider button design for Panço. You can check the functionality and design of it by visiting the link (mobile). Example picture of the design is at the end of the document. 
* Consider this exercise only for the mobile version of the website. 
* You can use javascript, css and html. Jquery or other js. libraries are not permitted. 
* Slider buttons must show up in this page and all the pages which the user can navigate through the slider buttons. 
* Calling slider buttons after filtering or sorting is a plus but not mandatory. 
* Buttons text and directions links can be found in the table below.  
* Your code must work when used in the browser console. Please submit your whole work. 

Atlet https://www.panco.com.tr/kiz-bebek-atlet/ 

Astronot https://www.panco.com.tr/kiz-bebek-astronot/

Body https://www.panco.com.tr/kiz-bebek-body/ 

Elbise https://www.panco.com.tr/kiz-bebek-elbise/ 

Eþofman https://www.panco.com.tr/kiz-bebek-esofman/ 

Etek https://www.panco.com.tr/kiz-bebek-etek/ 

Gömlek https://www.panco.com.tr/kiz-bebek-gomlek/ 


## Development Steps 

IMPORTANT NOTE: If you search “sliderbutton” in codefile, you can find code blocks fors lider button which I added to Panco codefile. 

1- Firstly all the html file of Panço website is copied. (ctrl+u / ctrl+a / ctrl+c) 

2- In the mean time, .css file, .js file and .html file of Twigy website is investigated/checked. 

3- Line of new slider button is detected in Panço html file. 

4- 2 div blocks are added. Both have same class yet diffirent ids. 

5- CSS codes are added between <style></style> blocks. New .css file is not created. @media used for visibility of blocks regarding to screen sizes. These div blocks will be visible if screen size have max 600px. Filter_items class is used to design buttons, selected and not_selected class are used for activation of buttons.

6- Javascript code is added between tickets. elements are added dynamicly in div blocks. First ticket is for “atlet” button. This button routes website to atlet.html. Other tickets are for other buttons.These button route website to directly http web sites. 

7- atlet.html code is copied from https://www.panco.com.tr/kiz-bebek-atlet/ link. Same buttons are added to atlet.html file. But atlet button is selected due to atlet items are filtered. So selected class is added to ticket of atlet button. 
