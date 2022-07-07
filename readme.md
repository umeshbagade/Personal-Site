**display property**

it has four values
block - it simply block the other elements from sitting next to it but we can set width to these elements
inline - it simply allows other elements to be displayed on the same line but doesn't allow to set its width
inline-block - this we can say the best version of all the pervious two values this can allow the elements on same line as well as to set their width
none- it simply hides the existance of the element(unlike visibility:hidden it does not allow space for that element)

some elements are by default block - p,h,
inline - span
 
**position**

this property determines the position of an html element in the page

1. relative-
we can manually change the position of element relative to the expected position(determined by browser) by specifying left,right,top, bottom;
only changing the position to relative doesn't make any change for that we need to specify the top,left,right and bottom

2. absolute-
This sets the position of a component relative to its relative parent. In nested structures, else relative to body

for absolute position its parent should have relative positioning else it will be relative to body  

3. fixed-
this fixes the position of the element relative to body, despite of scrolling

4. static-
this is the by default property, in this the browser tells the position of the element.
displays one after the other

**Font Size**
The Standard Font size is  16px==100%==1rem;
% and rem are adjustable according to the browser font size preference.