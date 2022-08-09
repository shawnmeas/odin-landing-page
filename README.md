# odin-landing-page
## Introduction (Written before starting project)
 This is the second project in The Odin Project course, falling under the "Foundations" section of the course. This project involves creating a website landing page, using a combination of HTML, CSS, and Flexbox. The page itself will consist of a total of five sections - four body sections, as well as a footer.

 For this project, two design images were presented. The first is a general mockup of the desired design, and the second lists the colors and fonts used in the design.
 * [Design Mockup](https://cdn.statically.io/gh/TheOdinProject/curriculum/main/foundations/html_css/project/odin-project.png)
 * [Colors and Fonts](https://cdn.statically.io/gh/TheOdinProject/curriculum/main/foundations/html_css/project/colors_and_stuff.png)

 This project will serve as an example of basic implementation of HTML, CSS, and Flexbox. It also serves as an example of taking a design mockup given without specifications and implementing it in a proper way to achieve the desired effect.
 ## Post Project Notes
 This project was certainly a step up from the first one, but still very pleasant to do. Being given the general design mockup and just having to figure out how to make it work (minus the notes about colors and fonts) was really an enjoyable challenge. And as far as I know, a pretty practical undertaking when it comes to the realm of web development as it relates to employment.

 While I had used some *very basic* CSS prior to starting The Odin Project, I had never really done anything too advanced. And I definitely had never looked into using Flexbox. I was really pleasantly surprised not only by how versatile it is in really getting a page laid out exactly how you want it, but also how easy it is to use.

 For the most part, I stuck with the project as its specifications stated. I did add a few extra things, however. For one, I put an image along with the logo in the header, and used `border-radius: 50%;` to make it circular. In order to vertically line this up properly with the accompanying text, I had to add `line-height: 0.75;` the the CSS for the text itself. In addition, I also populated the links to the header with relevant links to my SoundCloud music page, my GitHub page, as well as my personal webpage.

 I really only came across one issue throughout the entire process of this project, and that was at the very end. My footer wasn't properly sticking to the bottom of the page. Even after adding `height: 100vh` and `flex: 1` to the body CSS, it still wasn't filling the entirety of the page properly. Inspecting the page, I noticed that the body tag itself was using the entire page, just Flexbox itself wasn't working quite right. I looked back at the solutions for the full page layout tutorials, and noticed one had a separate div with the class name body, which was inside the body tag and contained everything except the footer. I did this, and added a `.body {}` section to my CSS and put the `flex: 1` in there, and that solved the issue.