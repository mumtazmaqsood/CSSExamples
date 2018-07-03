# CSSExamples
This repo has different css examples 

#Float
----------------
#Block elements always appeared vertically one after another, effectively limiting us to a single-column layout.

#“Floats” let you put block-level elements side-by-side instead of on top of each other. This is a big deal. It lets us build all sorts of layouts, including sidebars, multi-column pages, grids, and magazine-style articles with text flowing around an image. This is where we finally start creating real web pages.
note: Float-based layouts have mostly been replaced with Flexbox in modern 
#Left Align     #Center Align       #Right Align
float:left       margin:0 auto;       float:right;

#To summarize, when you have an extra unfloated HTML element at the bottom of a container div, use the clear solution. Otherwise, add an overflow: hidden declaration to the container element. The underlying idea for both options is that you need a way to tell the browser to incorporate floats into the height of their container element in order for their backgrounds to show up.
-------------------------------------------------------------------------------------------------

#FlexBox
--------------------------------
#flexbox gives us complete control over the alignment, direction, order, and size of our boxes.  Whereas floats only let us horizontally position and were originally intended for the magazine-style layouts.
#Flexbox uses two types of boxes that we’ve never seen before: “flex containers” and “flex items”. The job of a flex container is to group a bunch of flex items together and define how they’re positioned.

#justify-conten works for flex-items to align item horizentally 
            Other values for justify-content are shown below:
            center
            flex-start
            flex-end
            space-around
            space-between

#Gropping Flex Items is useful to manage website layout, it gives more control over desigin layout

# align-items:center, this property align items vertically, other values shown below 
                    #center
                    #flex-start   (top)
                    #flex-end      (bottom)
                    #stretch
                    #baseline
# Wrapping Flex Items
Flexbox is a more powerful alternative to float-based grids. Not only can it render items as a grid—it can change their alignment, direction, order, and size, too. To create a grid, we need the flex-wrap property.


