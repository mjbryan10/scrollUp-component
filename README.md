# scrollUp-component
A React component for scrolling up the page.

## Usage
Include both ScrollUp.js and scrollUp.scss in the same folder. 

#### Javascript options:

* Change height under scrollActivate, to adjust where the scroller will appear.
* Change targetPosition to adjust where it scrolls to.

#### Sass options:

* Depending where you want the scroller to appear on the page, change the option under .scroll-container to the appropiate option:
  - bottom : scroller will appear from the bottom of the screen.
  - left : scroller will appear from the left of the screen and stay on the left hand side.
  - right : scroller will appear from the right of the screen and stay on the right hand side.
  e.g. 
  ```
  @include entrance(bottom);
  ```
* $jump-height is the option to adjust the animation jump height
* $size will adjust the text and container size.
* $bg-color will adjust background color
* $bg-color_hover will adjust the color it changes to on hover event.
* $page-offset will adjust how far from the edge of the screen the scroller will be. 

## Example

An example of the scroller being used can be found on the [Bookstore demo](https://mjbryan10.github.io/bookstore-app/).
