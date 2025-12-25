# WHAT YOU HAVE LEARN IN CSS
# auto => tells the browser to auto calculate value based on content, container, or layout rules
# id name does not start with the number
# class select using dor(.) 
# select select elemtn by id using (#)
# can create multiple class example class = 'nav bar'
# comments are ignore by the browser
# hexa respresent the combination of rgb = #7d 8a 7c
# internally use rgb instead of the hexa
# opacity apply on current element as well as child element to avoid child use rgba 
# 3groove creates a sunken 3D border, while ridge creates a raised 3D border.
# groove = to show inword effect take color from the border
# ridge = to show outeword effect take color from the border
# overflow-anchor => it control scroll anchoring , it means prevents the page from jumpning when new message added and removed
# overflow => it prevent text from overflowing its container,
# overflow-wrap: break-word = > only when overflow while overflow-wrap: anywhere at any point even no overflow
# display = it is used to change the default behaviour of the html elements 
# inline = span, a, img
# block = div, nav, section,header,footer,h1
# max-width => it is used to make the content dynamic shrink according to the screen while in width : it does not happen
# static => it positioned always according to the normal flow of the page
# relative => it positioned relative to its normal position in document flow
# clearfix => it is used to when the element is flow outside the container 
# fixed => it positioned relative to the viewport it means it stay in the same place even if the page is scrolled
# absolute => positioned relative to nearest positioned ancestor if not parent element then it point to body of template,removes an element from the normal document flow and lets you place it exactly
# sticky => toggel between the fixed and relative, positioned relative unitill a certain scrolled position  reached and after the scrolled condtion reached it behave like fixed;
# z-index => specify the stack order of the element it means which element will come on the front and which will come behind
# float => it specifies to float the element left, right , and not at all.
# clear => this property pushes the floated element below on the left ,right,both side,
# clearfix => when you use float with left ,right the parent controller did not recognize the floating children and parent container collapse
# Note: It creates an invisible helper element inside the parent, right after its children.
# display:table => it make the pseudo element behave like a block level element
# inline => Does NOT accept width/height, stays in the same line, and only takes space equal to its content
# block => take full available width and height , always start with new line of each element 
# block-inline => accepts width and height but remail in the same line 
# clear:both => it pushes the pseudo element below the floating element so that parent can expand below
# center align the block element => margin: auto => horizontaly center the block element also specify the width to prevent element from streching out of its container
# center align image => margin:left/right = auto, and display:block and width to shrink the image size
# center with flex => align elements both horizontally and vertically take justify-content and align-items =  center
# center align item with grid => place-items:center;
# align with position,float   
#inherited properties => color, font-family, font-size, line-height and text-align it applied with the inline elements
#non-inherited properties => border, background, margin, height, padding,
# explict inherit works on both strong {
  border: inherit;
}
#border-image-source: url(border.png) = This takes your image and turns it into a border.
#border-image-slice:30 = 30px = image is slice in 30px in each side corner will become border and center will ignored
#border-image-width = control how border thick should be 
#border-image-outset 2 = 2px = border image extends outside the element 
#border-image-reeat: strech  =  strech image to fit border
                     repeat  =  repaet image multiple times
                     round = Repeat but adjust size to fit perfectly
                     space = add space beteen the repeat
