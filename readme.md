CSS - My Site

Resources:

https://www.favicon.cc/ - Create favicons
https://pesticide.io/ - Extension
https://colorhunt.co/palette/226680 - Color Pallette Used
https:fonts.google.com/ - Font Embedding
https://cssbuttoncreator.com/ - Button Creator Website.




CSS Intermediate Challenge
Lesson 1

1. Configure Boilerplate
2. Link External Stylesheet
3. Change BG color via CSS
4. Add Favicon: favicon.cc link like stylehsheet


Lesson 2
1. Use Divs to structure HTML content. Use Developer tools and Pesticide to help stylize.
2. Override Browser Default Margins and Set DIV to edge of LEFT, TOP, RIGHT.
3. Manually Setting Properties will override browser defaults.

Lesson 3. Box Model

1. Divs are containers. Use Pixels or Percentage. Percentage is Dynamic.
2. Borders are added around the Div's Dimensions.
3. Shorthand is best for adding Borders.
4. Div will adjust height and width automatically to fit content if not specified.
5. Padding is the Space between the content and the Div Borders.
6. Margin is the Space on the Exterior of the Div.


Challenge
1. Create 3 Div's TOP, MIDDLE, BOTTOM. Assign Classes and give different background colors to differientiate.# CSS-Box-Model
2. 3 boxes all 200px x 200px
3. 1st box: 10px border and 20px padding
4. 2nd box: 20px border
5. 3rd box: 10px border



REVERT SITE AFTER CHALLENGE

Display Lesson 
1. BlockElements: Takes up whole width. Many html tags default to block elements. examples, h1, p, div
2. InlineElements: Doesn't take up the whole line block. examples, spans, images, anchors
3. Span lets you stylize partial elements. Span is an inline element. 
4. Display lets you Modify Block type. example. display: inline-block;
5. Inline-Block lets you treat block like inline.
6. Display-None removes the element.
7. Visibility: Hidden Hides the element but holds the positioning on the page. 

CSS RULES
1. Content is Everything. Content is Priority on Dimensions.
2. Order determines layout order.
3. Children sit on top of parents. Z-Indexing.
4. Position: Static, Relative, Absolute, Fixed.
5. Static = Default
6. Relative = Property Changes are Applied on top of the default properties.
7. Coordinates: TOP, BOTTOM, LEFT, RIGHT. Example. img { top: 50px}  Positioning behaves similiar to margins
8. Relative doesn't reposition other elements. Like another layer.
9. Absolute: Positions element relative to parent element. The Naming is confusing but thats how it works. 
10. Absolute removes the elements from the flow of the document. Other elements behave as if it doesn't exist.
11. Absolute is alot easier to reposition elements when relative to the body.
12. Fixed holds the element to that position when you scroll. Great for a Navbar/Sidebar
13. Text-Align needs to be utilized on the parent element to center all the child elements, unless width has been specifeid.
14. Margin AUTO lets you auto center elements with width specified. example margin: 0, auto, 0, auto; centers horizontally.


Font lesson

1. WebSafe Fonts have the best success rate with many devices.
2. A font-family used with a stack is has the best success rate. 
3. Font embedding is a way to help all devices see the same font. fonts.google.com

Font Challenge 

1. CHALLENGE: Set the text colour for the h1 and h2 to both be the colour with hex code: #66BFBF
2. CHALLENGE: Set the text colour for the h3 and anchor tag to be the colour with hex code #11999E
3. CHALLENGE: Change the “a programmer” subtitle to font weight: normal.
4. CHALLENGE: Change the line height to double what it currently is.

CSS Float and Clear Challenge
1. Make each skill row only 50% of the width of the screen.
2. Make each skill row have 100px margin top and bottom. 
3. Make the skills text left-aligned.
4. Double the line height of the skill row.
5. Make each skill row image have the 25% the width of the skill row.
6. Use float to put the 1st image to the left of the text in skills section.
7. Create 30px space between the  1st image and the text.
8. Use float to put the 2nd image to the right of the text in skills section.
9. Create 30px space between the  1st image and the text.
10. Use float to prevent the wrapping on both paragraphs. (removed due to aestethics)

* Clear is like an anti-float. Prevents the wrapping.
* Only use float when neccesary and only use for text wrapping.



CSS Challenge 

1. In this lesson, you can download the end specification for how we want our website to look. It’s PDF specification that shows you how everything should roughly be laid out and what are the colours and sizes of all our elements on our web page. 

LINK - https://drive.google.com/uc?export=download&id=1vrdEeFZKcv1XZOK6yLMAEq6mPxz6K2Bg



Use this file as a guide to modify the CSS of our current website to make it resemble the specification.



NOTE: In order to create the buttons in the specification you’ll need to head over to this site and edit the button then copy and paste the CSS.