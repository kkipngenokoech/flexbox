This is a readme about flexbox.
Flexblox is a way to arrange items into rows and columns.
This items will flex (that's grow and shrink) based on some simple rules that you can define.
anything that has a display flex on it is a flexbox
a flexitem is anything that lives inside a flex container.

## The flex shorthand
The flex declaration is actually a shorthand for 3 properties that you can  set on flex item.these properties affects how flex ow items size themselves within the container
 flex has flex-grow, flex-shrink, flex-basis
 flex: 0; - flex-grow: 1, flex-shrink: 1; flex-basis: 0;
#### flex-grow
flex-item's 'growth factor'
flex: 1 is applied to every div hence all the divs would grow equally.

#### flex-shrink
'shrink factor' - this only comes into play if the size of the items are larger than their parent containers.

#### flex-basis
flex-basis is given in percentages.
it sets the initial size of a flex item, so that any flex-shrinking or flex-growing starts from this baseline.

## axes
the x and y axis( main and cross axis)
flex-direction: row (main-horizontal, cross-vertical) - this is the default setting when we set display : flex

## alignment
justify-content : space-between - instead of flex: 1 grows and shrinks the items to fill the available space. ; it aligns items across the main axis
cross-axis  alignment uses the align-items tag with values i.e center
## gap
adding gap to a flex-container places spaces between the flex items
