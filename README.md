# Code-Refactor
Homework Week 1 - Code Refactor<br>
Author: Foti Mougos

### Brief:
The customer Horiseon has not requested that we perform any changes to the content or styling of their website. They have requested that we improve the readability & maintainability of the code in their website. They have also requested that we ensure all links and images display correctly.

### Lessons Learned:
Theres alot you can achieve with CSS that I thought was only possible/easy with jQuery libraries or bootstrap classes. HTML and CSS are reasonably forgiving if you have syntax errors. You can write elegant HTML without needing comments. Floats work in.. wierd ways. They are particular about the amount of pixels left on the page, so you have to be careful about using percentages with specific (px) sizes

### //CHANGES:
#### CSS
[X] Fix bugs in CSS (some quotes missing)<br>
[X] Find out if * is valid CSS selector - yup universal selector<br>
[X] Site behaves badly in mobile resolution - solved via display: table; css and display: flex for the header.<br>
[X] Banner & Buttons display poorly in iPad resolution - tweaked li margin slightly (22px) to make it fit.<br>
[X] CSS file has sensible spacing & formatting<br>
[X] Consolidated a bunch of CSS tags that were for similar elements<br>
[X] Removed redundant CSS properties<br>
[X] Shifted around CSS properties to be near children i.e. .benefits comes before .benefits img and so on<br>
[X] Made header 'fixed' position to be always visible & allow for easier navigation<br>
[X] Added margin to content images <br>
[X] Adjusted margin in content and benefits sections to be percentage based. 70% for content, 20% for benefits, which leaves 10% for margins here (width wise)
[X] Added media tag and fixed responsiveness for EVERYTHING.

#### HTML
[X] Basic title - make it more descriptive/sensible<br>
[X] Empty .hero div? Is it needed? - yup its the big picture<br>
[X] Alt attributes should work - tested by borking the src on the images<br>
[X] SEO anchor not working - missing ID on the section<br>
[X] HTML file has sensible spacing & formatting
[X] Added some hr tags to split the content in the Benefits section

#### Customer Objectives
[X] Change Divs to more 'semantic' elements i.e section, header etc<br>
[X] Assess 'logical' structure of HTML - heading sizes cascade, i.e. we don't have H1's inside of divs with headings of H2 type

