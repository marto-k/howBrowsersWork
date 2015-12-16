#howBrowsersWork
---
##Explanation
---
How the parsing of urls to get information works.*behind the scenes*.
(https://arvindr21.github.io/howBrowserWorks/#/)


These are the ones that appear on a webpage consisting of the body and the css styles.There also are *Nodes* which classify characters in the body tags.
Lastly  **DOM**  which is used to build a tree consisting of all material for a website.


##Parse, Render, Layout & Paint
---
See image in  <https://arvindr21.github.io/howBrowserWorks/imgs/dns/8.png>

###These are the four steps
---
1-Parsing html to construct the DOM tree


2-Render tree construction


3-Layout of the render tree


4-Painting the render tree


###Parsing html to construct the DOM tree
---
Here the keyed url goes though proccesses before it parses to your server.From **network** to the **DOM** which is the **Document object model**

Open this link to view steps...


https://arvindr21.github.io/howBrowserWorks/imgs/flow3.png

###Render tree construction
---
DOM Tree and CSS joined equates to Render Tree
CSS Box Model
Only visual elements are in the render tree
Not part of render tree

Open this link to view outline...

https://arvindr21.github.io/howBrowserWorks/imgs/renderTree.png

###Layout of the render tree
---
Here the size/position of the render tree is specified.


**For example:**
https://arvindr21.github.io/howBrowserWorks/imgs/render3.png
After you determine the position and size of the render tree the layout in the *DOM* changes.

###Painting the render tree
---
This is the final step where you furnish the characters in the render tree.This can be don e using script language .
You can make use of paintslow(); and paintfast(); which changes the speeds and uotlook of render tree.


Chechout this link image *example*...(https://arvindr21.github.io/howBrowserWorks/imgs/ebf0.png).
