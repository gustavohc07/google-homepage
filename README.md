# google-homepage

First project from TOP. Will rebuild the homepage from google using HTML and CSS. At first, there is no need to add advanced properties, like hover, drop-down menus, etc..

First thoughts: 
	
	Maybe it looks simple to you, but it is exciting for me. Probably I'm going to tackle the difficult task too.

                           ------------------------------------
Time to complete the task: 8 hours approximatelly (research + coding)

Final thoughts:
	
	More difficult than expected. Positioning elements was the toughest part. I'm still a little bit confused with it. Probably am going to practice flexbox and grid for a while.
	There were some doubts during this project that I will list it down (you don't need to read it, really):

	1 - How to resize an image? We can just add height and width in the image tag. Remember that Chrome, when working with flexbox, stretch images by default.

	2 - How to select input in CSS? I manage to select it by defining a class for it. There is another way by calling "input [type="value"]"
	3 - How to put logo in a tab? I searched that. It worked by setting in the head section <link rel="shortcut icon" href="images/favicon.ico">
	4 - How to position elements? That was a tough question to answer. There are tons of "how to" with you search in the web. I worked with flexbox but you can make it with grid too.
	I got tons of problems here till I figure it out how flexbox works and still, I don't know how I manage to stick the footer at the bottom of my page. Maybe it was magic, maybe it was not...
	5 - How "position" actually works? I learned a lot about it. Still need some practice tough... But I work it out with my icon inside the text form. It was a nice way to apply the knowledge and see how it works.
	6 - How to work with box-shadow? Just searching css-tricks I manage to make the trick (no puns intended)
	7 - THE FOOTER. The toughest part of this project for me. I managed to work it throught by setting "margin-top: auto;". Still, don't get it how this works, but the footer sticked at the bottom of my page, so I got this going for me.


	At "First Thoughts" I said that I would probably tackle the difficult assignment. Well, I will not for now. I will work it through it later.



Notes during project:

/* Why does't work just .header? Why I need more specificity to work it throught?
Got it. Setting the header's class as container and container as a flexbox, all the items inside
it is an item for the flexbox. Therefore, `<ul>` acts as a whole item. */

/* .header ul {
    width: 100%;
    display: inline-flex;
    flex-direction: row;
    justify-content: flex-end;
    border: red solid 1px;
} */

