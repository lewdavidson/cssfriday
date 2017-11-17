# _Shun Knife Co._

#### _A web store, November 17, 2017_

#### By Lew Davidson.

## Description

A web store advertising the Shun Icon knife. Includes a summary, photo gallery, size guide, and sign up form.

## Specifications
| Term | Description | implementation |
| ----- || --------- || ------------- |
| border-box | tells the browser to account for any margin or padding that I give an element. The width and height will include the margin and padding, shrinking the content inside instead of the whole element. || I used border-box on the whole page to make it easier to give all of my styling exact dimensions and spaces on the page. |
|float| the float's value tells the page which side the element should be on and tells the content to flow along side of it, instead of going inside of it.|I used it on my columns and nav bar to keep both sides separate upon resizing the page.|
|display:block|tells the element to display on a single line, taking up the full width of the page.| I used it in my page break to tell the dotted border to take up the full width of the page.|
|display:inline|tells the element to only take up as much space as it needs to. Or as much space as you specifically tell it to.|I used inline in my nav bar to keep the right-hand elements from trying to overflow into the hero image.|
|centered content| objects that are centered on the page. Can be anything (images, text, tables, etc.)| I used the transform(translate) property to center my table and form on the page.|
|pseudo-element|something added to a selector to change a specific part of that element| I used ::after to add a little arrow after my checkboxes, asking the user to select and option.|
|pseudo-class|adds an effect to a selector based on an action.|I used :hover and :focus to style my buttons, nav bar, photo gallery, and my form-fields.|
|clear-fix|prevents a parent element from collapsing when there are only floated elements inside of it.| I used it in my nav bar paragraphs and my right column to prevent the parent from collapsing.|
|positional selector|The only one I know is :nth-child which tells the page to select a specific child from it's parent and style it.|I used it on my left column list to turn the last item red.|
|selector combinator| when you use two or more types of selectors together for specificity (ex. .col-left li)|I used them all over my page in order to specifically style many areas of my page.|

## Setup/Installation Requirements

#### GITHUB PAGES
* Open web browser and go to the [GitHub Pages][4].

[4]: https://lewdavidson.github.io/shun-knives/index.html "GitHub Pages"

## Known Bugs

No known bugs at this time.
Tests were successful.

## Support and contact details

_Feel free to contact Lew at lewdavidson47@gmail.com with any feedback or questions._

## Technologies Used

* _HTML_
* _CSS_
* _Google Fonts_

### License

Copyright &copy; 2017 **_Lew Davidson._** Student at Epicodus.
