
.parent {
	display: flex; /* or inline-flex */

	flex-direction: row | row-reverse | column | column-reverse;
    
	flex-wrap: nowrap | wrap | wrap-reverse;

	justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly | start | end | left | right;

	align-items: stretch | flex-start | flex-end | center | baseline | first baseline | last baseline | start | end | self-start | self-end;

	align-content: flex-start | flex-end | center | space-between | space-around | space-evenly | stretch | start | end | baseline | first baseline | last baseline; 

  	/* GAP */
    gap: 10px;
    gap: 10px 20px; /* row-gap column gap */
    row-gap: 10px;
    column-gap: 20px;
}
.children {
    order: 5; /* default is 0 */

    flex-grow: 4; /* default 0 */

    flex-shrink: 3; /* default 1 */

    flex-basis:  33.33% | auto; /* default size auto */
    /* Shorthand */

    flex: none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]

    align-self: auto | flex-start | flex-end | center | baseline | stretch;
}

