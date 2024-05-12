# Techium CSS
## General
There is a max width for the page. A number of pixels that regardless of the size of the screen the elements cannot exist. I believe I can do a percentage rather than pixels. Then use a media query to change this percentage when I get to smaller screens.

## Sections
### Header
Background black.

### Services
Background white

### Works
Background black.

### About Us
Background white.

### Latest News
Background white.

### Testimonials
Background white.

### Contact
Background white.

### Footer
Background black.

## Elements
### Navigation Bar
Grid to align logo to the left and navigation links to the right.

### Large banner text
Color to be white

### Button
Red border
White color text

### Section Header
Use mix-blend-mode: difference to set the header to black when the background is white and vice versa

### Section Sub Header
Capitalised
Red

### Services Grid
Use a grid to display the content allowing it to scale up to a 2 by 3 matrix and scale down to a 6 by 1 matrix.
Work with percentages and grid logic to accomplish this.

### Works Pictures
Use a grid to allow them to scale up to either a 1 by 3 matrix or 3 by 1 matrix. No other options.

### About Us Body
Use a grid to align the picture to the lef side and the text to the right side.
This is less messy than using float logic.
This means I will need a div specifically around these two to prevent them from affecting the button, header and sub-header.

### Latest News Body
Use a grid to align the elements to either a 1 by 3 matrix or 3 by 1 matrix only.
The pictures should all be a constant size and the text will occupy the rest of the element. This means that the size of each grid element should be the same but the contents will have different appearance levels.

### Testimonials Body
Use a grid to align the elements to either a 1 by 3 matrix or 3 by 1 matrix only.
The pictures are to be circles and equal sizes.
The text is to be center aligned.
The citations are to be in red

### Contact Body
The text is left aligned.

### Footer body
Use a grid to align the logo and address to the left and the social media icons to the right.
After the horizontal line use a grid to separate the copyright and extra information. Align the copyright left and the extra information right.
Text color mix-blend-mode: difference
