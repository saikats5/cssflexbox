# cssflexbox

Parent --> Flex Container(display, flex-flow, justify-content, align-content, align-items)
Children --> Flex Items(order, flex, align-self)

display: flex; //taking full width // on reduction children also reduce
display: inline-flex; //takes limited space till it's children // on reduction nothing reduces 

flex-flow: row nowrap; //flex-direction flex-wrap
//wrap //goes down on resize //wrap-reverse
//column //everything goes down //fixed width doestn't reduce //row-reverse

Main Axis(top left to right(row)/top right to left(row-reverse)) vs Cross Axis(top to bottom)
Main Axis(top to bottom(column)/bottom to top(column-reverse)) vs Cross Axis(top left to right)

align-items: stretch; //center //flex-start //flex-end //baseline based on content //refers to cross axis
justify-content: center; //flex-start //flex-end //refers to main axis

align-content: center; //space-between //refers to cross axis when we have items in more than one line