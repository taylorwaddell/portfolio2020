# Portfolio Project – 2020
New portfolio landing page. Designed and coded by myself.

# Design
## Design Process
I spent far too long designing this one. I started with sketches and pulling inspiration from Pintrest which was fruitful. But this led me to wanting a new logo. Luckily a pretty simple one popped into my head that worked perfectly. So I through that together real quick in Adobe Illustrator. After that was complete, I used Adobe XD to design a iPhone X prototype of the website, followed by a 1366px template web design.
## Design Explained
The primary focus for creating this portfolio was to practice the coding techniques that I have been learning over the past few weeks. Yet, I also wanted to make sure it was at least mildly responsive (I'm limited by my coding knowledge at the moment). With this in mind, I wanted to design a website that was more on the minimal side with lite usage of unique elements. Just enough to stretch myself in my coding practice but not too much to where it would take too much time.
### Colors
I based the colors of the picture. The majority of the text has a teal-esque color that was sampled from the Patagonia© hat on my head. I liked this idea because the hat was the only element in the picture with that color and it was on my head. This symbolizes how the website is basically just an about me page.
### Fonts
I used a font called Lust from the Adobe TypeKit. I really appreciated the Times New Roman aesthetic but with a bit more 'mmph' to it. The thickness makes it stand out and the exxageratted serifs make it a little more fun and luxurious feeling. As a supporting font I stuck with Helvetica; 1. to keep it a little more simple on the coding side, and 2. to keep it easy on the eyes.

# Code
## Coding Process
To build this site I used Atom on my local computer and then uploaded the files here to share and host. Keeping the design minimal allowed be to pump out this site pretty quickly. It's lack of complicated organization and padding mean't, for the most part, I was able to simply center things or align them. I also used Adobe TypeKit's web feature to embed the font "Lust" into the site. I also used svg's for the social logos in the footer which saved me a massive amount of time.
## Lessons Learned
### Placing Logo Over HR
I did have a bit of a tricky time placing the spinning logo on top of the horizontal line. I was running into a problem where I could get the logo exaclty where I wanted it using ``` position: absolute ``` and then just adjusting left or right. But this prevented the logo from being responive to the browser window which resulted in it staying where it was relative to the window instead of relative to the design. After fumbling around with it and researching for far too long, I ended up just doing ``` margin-top: -5% ``` and this seemed to do the trick!
### Using CSS to Spin Logo
Learning to spin the logo was so much fun. I heavily utilized [this tutorial](https://flaviocopes.com/rotate-image/) so shoutout to them! I pretty much followed their tutorial exaclty. I did make some minor adjustments but I also added a ``` @keyframes backrotate ``` feature which allowed me to do a ``` :hover ``` effect. I wanted the logo to stop spinning and go back to its upright position when the mouse was hovered over it. This took some playing around with. The problem I was finding was that it would rotate to the ``` backrotate ``` starting position before starting the rotation. I solved this by changing the start position to ``` 45 deg ``` and applying ``` animation-timing-function: ease-out ``` as well as ``` animation: backrotate 70ms linear ```. This seemed to solve the problem!

# Resources Utilized:
- [How to continuously rotate an image using CSS](https://flaviocopes.com/rotate-image/)
- [FONT: Lust – Design by Neil Summerour](https://fonts.adobe.com/fonts/lust)
- [ICONS: Adobe XD Plugin | Icons 4 Design](https://holla.today/tpost/04dspdr37m-icons-4-design)

# Apps Utilized:
- [Adobe XD](https://www.adobe.com/products/xd.html?sdid=12B9F15S&mv=Search&ef_id=CjwKCAiAxKv_BRBdEiwAyd40N4JTpEUKjhxPVlSPMlcSKP1E_AXjeu3t4W1TZ7M9eiX8YKzIhfOgJxoCy84QAvD_BwE:G:s&s_kwcid=AL!3085!3!394015009825!e!!g!!adobe%20xd!1641846436!65452675151)
- [Adobe Illustrator](https://www.adobe.com/products/illustrator.html?sdid=KKQML&mv=search&ef_id=CjwKCAiAxKv_BRBdEiwAyd40N1W6s2meZlYyUk8X3mfKxI6EB7DLVFRgJfP31BMwf9n1LQAztp8I5hoCM7IQAvD_BwE:G:s&s_kwcid=AL!3085!3!442365417815!e!!g!!adobe%20illustrator&gclid=CjwKCAiAxKv_BRBdEiwAyd40N1W6s2meZlYyUk8X3mfKxI6EB7DLVFRgJfP31BMwf9n1LQAztp8I5hoCM7IQAvD_BwE)
- [Atom](https://atom.io/)

Go have fun. - Taylor
