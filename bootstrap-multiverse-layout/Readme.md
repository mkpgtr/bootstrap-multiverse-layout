
# This project is meant as a submission to an assignment I have been given while learning full-stack-development. Naming the platform might violate some rules. Due to which, I think it's best to discuss the assignment based on the general terms. I am very grateful to have got this Assignment. The best part is that there was a lot of room for creativity.

1. I absolutely loved building this project.


# Assignment requirements Completed :

1. Built navbar with nav-pills.
2. navigation bar has contact section.
3. A list of artists lives in the dropdown.
4. Clicking on the dropdown item will lead to single-artist-page details.
5. Added my personal purple-blueviolet theme to distinguish it from a typical bootstrap-looking-website.


# Purpose of README.md

1. I learnt this from frontendmentor.io.
2. It helps the viewers of my code to understand what my project is all about.
3. It also helps me to clarify why I did things the way I did.
4. It gives a personal touch of originality to the project. These days copy-pasting HTML & CSS(thinking they are not important) is common. I personally feel that HTML & CSS teach us a lot about writing code. In my experience, writing HTML & CSS has made me appreciate the value of Javascript more.
5. It helps my teachers to see my code and see my reasoning why I chose a certain method over others.
6. It helps anyone who is struggling with a particular problem to get and resolve it.

# Original Work

1. This is my original work. Certain code which was working working I have taken help from stack-overflow. For Example, fixing overflow issues, looking how to change default bootstrap styles and things like that.

2. The design's color is inspired by my previous project : https://dreadnought-for-desktop-by-manish-v2.netlify.app/. This project was not responsive. So when I learnt Bootstrap I thought it's a good idea to make something responsive with this beautiful blueviolet-theme.

3. As a guitar player myself, I have always been intrigued with beats and music and spiderman in general. So I decided to make this project - artist-centric.

4. The netlify website says that 'Develop and deploy websites in record time.' Although I deployed this on record time, I developed this writing the CSS myself across a span of three days. No tools & frameworks were used except Bootstrap.


# Concept behind the pages

1. There are four artists namely : Tom Holland, Eminem, Tim Henson and Iron Man. 
2. They have a manager : JayZ.
3. That's why when you go to the Contact Section of the page you will see the Contact Form and some info about JayZ.


# Let's talk about weird things first


## The first weird thing:

1. When scrolling down the individual artist section, one might get the illusion that the scroll-bars interfering with the user's ability to scroll.
2. Please click on the shining purple area and then try to scroll.
3. This is happening on medium devices.
4. I have opened this page on Iphone 6S and it works well.
5. Also as we scroll by dragging, on mobile screens, it is working well too.
6. Please email me at mkpgtr@gmail.com if you find any problems apart from these regarding scroll.

1. The most weird thing I encountered was the index.html's Bootstrap grid layout.
2. the following code `


     <div class="row d-flex flex-column gap-2 flex-md-row justify-content-center justify-content-around cards-container align-items-strech justify-content-lg-center justify-content-xxl-between">
        `
        <!-- This part is weird -->
        <div class="card col-4 col-md-3 col-lg-2 bg-body-secondary home-custom-card-styles"></div>
        <div class="card col-4 col-md-3 col-lg-2 bg-body-secondary home-custom-card-styles"></div>
        <div class="card col-4 col-md-3 col-lg-2 bg-body-secondary home-custom-card-styles"></div>
        <div class="card col-4 col-md-3 col-lg-2 bg-body-secondary home-custom-card-styles"></div>
        
     </div>

` just worked right!

3. But my problem is that I don't know it does not feel quite intuitive to me.
4. Let me put it more clearly : col-4 will make the card take 4units out of 12units on the small screen. 
5. On medium screens, it will take 3units, and on large screens it will take 2 units.
6. The reason it fits well on large screen is that total 8 units are used and the four remaining units might have been taken by the spacing - from the gap-2 property.

7. Well that was that.

8. Next, I found evidence. Why it felt weird?
9. In the Invidual artist section I took a more intuitive approach :

`
<div class='row'>
 <div class="col-12 col-md-6 col-lg-4"> </div>
 <div class="col-12 col-md-6 col-lg-4"> </div>
 <div class="col-12 col-md-12 col-lg-4"> </div>
</div>

`
10. This helped me achieved the griddish appearance on medium devices.


# Things I have done in this project :

1. used nav-pills for the navbar

# Things I could have done(Things I noticed after deploying on netlify):

1. Defining more custom variables in :root so that my webpage feels more consistent.
2. I could have made a better design for the 2nd column for single artist page.
3. I could have avoided a lot of repetitive stuff if I had named classes more consistently. 
There are redundant classes which don't do anything. And because I wrote the CSS acrossa span of three days, sometimes I forgot I had defined certain classes after having a good night's sleep.

4. Added more margin-top to the home button on collapsed navbar for mobile screen.
5. The form section could have been a lot more funkier.
6. Clicking on the Read More button leads to the single artist page. However, I could have made it in such a way that : clicking on the card should have led to the single artist page.


# I have tried writing as much comments as possible.


# Custom Styles

1. I have customized many things so that my webpage does not feel 'bootstrap-ish'.
2. I have used utility classes by first defining them myself. Classes like letter-spacing used on Tom Holland Page 2nd Column 2nd Image are testimony to this.


# I struggled with horizontal scrolling issues and fixed them via stackoverflow

1. Mobile device horizontal scrolling was a major problem I found out when I tested my webpage.
2. I fixed it by using a code snippet from stackoverflow.com.
3. The same has been mentioned in the css comments as well.

# I also took help from stackoverflow regarding Input Field Outline.

1. Bootstrap input field wide border and Outline gets triggered in the input:focus state.
2. I tried many things but when nothing worked, stackoverflow snippet worked like a charm.


# Things I learnt and loved during this project:

1. I loved how easy it is to make responsive webpages using Bootstrap.
2. I learnt how to show and hide content using bootstrap responsive classes on different screen sizes.
3. I loved how I fixed navbar issues when they popped up. Sometimes I was able to fix them without my best friend Google.
4. HTML & CSS seems like a breeze with Bootstrap. Also, customizing Bootstrap is super-easy.
5. I also found out how useful SASS is. 
6. I once again felt the joy of writing CSS. The more I write CSS, the more I understand the value of 'Best Practices'. 
7. Writing my own utility classes helped me how I can use this idea when writing Javascript also. Writing maintainable code is an art.
8. I have got into a habit of reusing similar patterns from my previous projects to build different-looking layouts.
9. I learnt how to make a Bootstrap webpage look not-Bootstrapish!


# The GIF changed the look of the entire webpage.

1. It's easy to get lost in the hype and the information overload of the internet era.
2. Sometimes simple things can bring so much change.
3. The space-like feeling this webpage gives me is entirely because I searched the keyword : 'aesthetic GIF on google'.
4. I use GIFs in most of my images.

# There is always a lot of room for mistakes and improvements.

1. If you find any, please email me at mkpgtr@gmail.com
