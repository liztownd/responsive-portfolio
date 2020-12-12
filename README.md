# responsive-portfolio

Creating a responsive portfolio using only Bootstrap css - no personal css.

Bootstrap is described as follows (from <a href="http://www.wikipedia.com">Wikipedia</a>)

```
Bootstrap is a free and open-source CSS framework directed at responsive, mobile-first front-end web development. It contains CSS- and (optionally) JavaScript-based design templates for typography, forms, buttons, navigation, and other interface components.

```
Utilizing Bootstrap allows one to easily create responsive website design.

For example, for the navigation bar, on smaller screens the links collapse into a hamburger icon:

Large screens show the full range of links:

![text-full screen layout](assets/images/Nav-Full.png)

Small screens show the hamburger icon with a drop down menu:

![text-small screen layout](assets/images/Nav-Hamburger.png)


The navbar was copied from Bootstrap, then modified. A background color and padding was added to the navbar header : `bg-info` and `p-3` to make the blue box around my name. `ml-auto` was used to justify the links to the right. The `search` box was removed.

For the Portfolio page, a grid system was utilized to showcase my graphic design images. I did not use responsive images on the Portfolio page so the images would be large enough to see even on small screens. I put a break-point into the code so on smaller screens the images would form only one  long column to allow for the larger  picture size.

On the About page, the image is responsive, so it will leave space on the right for the text. It was also laid out utilizing the grid system and columns.

The social media icons on the About page came from <a href="https://www.iconfinder.com"> www.iconfinder.com </a>.

The form on the Contact page was also copied from Bootstrap and modified.

The html was validated using <a href="https://www.freeformatter.com/html-validator.html">www.freeformatter.com/html-validator.html</a>.
