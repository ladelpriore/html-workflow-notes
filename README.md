# HTML and more it Workflow

## HTML
The main structure of your website
index is the main file name
html is the type of document
a - hypen makes
- Elements -> what the browser reads and displays to the user
- tags
        - name
        -opening and closing tags
        - tags are the part iwthout the text
        - opening tag is first: it's less than, tag, then greater then
    -content -> whats in b/t the tags
        -no line gaps in between the start and end tags will show on the webpage, so make line breaks for thesake of clean coding

-general structure of an HTML page
- html -> contain all other elements 
- head -> information that the user will NOT see on the page. This is also known as Metadata.   
    Shows up on the web browser tab name. (it's info the user won't see. it's data on the inside.)
        The html element contains the header inside it
        The html element is the parent of the header element
        The header element is the child of the html element
        Parent vs child element
    Anything <head> </head> within the head element wont show on the webpage.

- body -> information that will be shown on the webpage, once the head element is closed
     You don't have to have a body for the title to show on the page. 
     Nevertheless devs keep the full html elements and tags because they value consistency! So include the elements standard. 
     Standards of organization!

- formatting "rules" 
	- HTML files should be named in lowercase and separated by hyphens
	- convert tabs to 2 spaces
	- avoid leaving trailing spaces
	- put each element opening and closing tags on their own lines
	- indent each element that's child to another element
	- main element doesn't change the header 

	-Semantic elements -> named absed on what's inside of the the elements
		-header -
		-main -> main content. Amazon's main content is the products users are looking through to buy
		-footer - at the bottom containing contact info, special links, back to top link. These are special offers for focused use. 
		- h1-h6 -> header 1. This isn't the same as the header semantic element. Header 1 is the largest title. Header 6 is the smallest title. Most websites are h1-h2. Rarely is h6 used cuz it's tiny!
		-nav -> navigation, nav bar
	-attributes -> give additional info for the element
			-<a> -these are links but they require an Attribute as a link to send the user somewhere
			-<target> specifies exactly 
			-<article> Articles keep it organized. Each h1 in an article is itws title and paragraph. Use article to seperate sections of content. 
			-<section> -> similar to article. It's a grouping of content. 
			-img -> image -> Include a description for devs or impaired ppl. It helps them see what's there. Use alt to indicate text. Image has no closing tag! Only the opening tag! An image tag has no content! IT is an attribute. 
			-ol/ul -> ordered list (numbered)/ unordered lists (bullet points). <ul></ul>


-advantages of semantic HTML
	-SEO
	-Accessibilty (screen readers)
	-Human-centered design. Working with humans is easier if there's text and order to read into

-troubleshooting and debugging
	-Alqways write and test your code as you
	-are u missing a closing tag?
	-are there spelling errors
	-parcel (comment) out certain parts of the code to find the broken code. (How was he able to highlight 1 code line at a time and see it highlighted on the html web page? Ask this.)
			CHrome DEV Tools - function F12 or richt click & inspect!


## More Git Workflow
-Merge Conflicts: When 2 ppl change the same file without pushing/pulling the changes first. 

-Branches
	-git checkout -> change branches
		- -b <feature-name> -> create a new branch. e.g. git checkout -b <Feature-A>
	- allows working on a new feature without affectin ghte main branch (productION)
	-very important when working in groups

-Pull Request
	-its when we are bringing out code to the main branch, push it up to Github, u r requesting that ur code branch be pulled into the main branch
	-someone else needs to review the code, see if it works, code review, see if it includes anything it should
	-allows code review, 2nd eyes should test through it for bugs! Think of test situations
	-1st person -> Github -> make a pull request (at the top)
	-2nd person -> goes to Github -> Review the commits on the Pull Requests -> Approve and merge OR tell person 1 to make some changes (it's a positivei process of coming up with the best possible code and project. it's not criticism or judgment. U wanna ask why they coded it this way. 
	-In a code review, u wanna ask, What is this code doing? Can u walk me through it? Line by line. Okay I see how u did and why u did it.
	-Bad: the code is accepted without reivew and merged without testing, and clients discover the bugs!
	-Keep it objective. It's not about "bad code." 
	









