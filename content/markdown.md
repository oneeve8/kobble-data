# Markdown Notes

Click the pencil icon in your Kobble Views to edit a markdown file in Kobble.  
The Markdown view is separated into two windows:  
The Markdown syntax is in the top window  
The result appears in the bottom window.  
Both windows scroll down.  
(Toggle back to the paper icon to select result view only)
***

# Header

Use a \# hashtag and a space before the heading:  

Syntax Examples:  

H1 = \# Markdown Notes

H2 = \## Markdown Notes  

(adding more hashtags makes headings smaller).  

Result Examples: 
## Markdown Notes (H2)
### Markdown Notes (H3)
#### Markdown Notes (H4)

***

# Soft Break

A Soft Break adds a new line without a break. To add a Soft Break,
insert two spaces after each new line.  Since you will not be able to see spaces, we will use dots to represent the spaces in the Syntax example.

Syntax Example:  
Ordinarily, you would have to use a double return which results in a hard break space between each line, like this:

First Line

Second Line

Third Line

However, you may want your lines to appear without the space between them, so that is why you would want to use a soft break. This is the syntax for creating soft breaks with each dot representing a space:  
First Line..  
Second Line..  
Third Line..  

Result Example:  (this is actually how it will look)

First Line  
Second Line  
Third Line
***
# Italics

Use _ , or * (one underscore or asterisk before and after words),  
Syntax examples:  
\_italic words\_  
\*italic words\*

Result examples:  
*italic words*  
_italic words_ 

***

# Bold

Use __ or, ** (two underscores or two asterisks before and after words),  

Syntax example:  
\_\_this is bolded using two underscores\_\_  
\*\*this is bolded using two asterisks\*\*

Result Example:  
__this is bolded using two underscores__  
**this is bolded using two asterisks**

You can combine them if you want both italic and bold
***


# Fenced code block
Use ```(forward quote before and after)

Syntax example:  
\```this is a code block\```

Result example:

```this is a code block```  
***

# Scratch
Use ~~ (two tildes before and after words)  

Syntax Example:  
\~\~scratch this\~\~

Result Example:  
~~scratch this~~
***

# Block quote  
Use > and a space before the quote

Syntax Example:  
As Mahatma Gandhi said:  
\> An eye for an eye only ends up making the whole world blind.

Or:

As Mahatma Gandhi said:  
\> An eye for an eye  
\> Only ends up making  
\> The whole world blind  

Result Examples:

As Mahatma Gandhi said,

> An eye for an eye only ends up making the whole world blind.  

Or:

> An eye for an eye   
> only ends up making   
> the whole world blind.  

***

# Link  Ask Bill why this does not work the link does not open in a new window? Or try another link?
Syntax Example:  
\[wikipedia]\(en.m.wikipedia.org), 

Result example:  
[Wikipedia](en.m.wikipedia.org)

***

# Horizontal rule

To create a horizontal rule, as is used between these tutorial sections, use three hyphens separated by spaces,  
Or: three asterisks, or three underscores without spaces between them

Syntax examples:

\- - -

\***

\___

Result example:

***

# List 
To create a list use an asterisk * with a space before the list item to create a bullet point, or just use numbers.    
Indent and then use an asterisk * for a hollow bullet point.

Syntax Example:  
\* Milk  
\* Eggs  
\* Butter  

Or:
1. Milk
2. Eggs
3. Butter

Result Examples:

* Milk
* Eggs
* Butter

1. Milk
2. Eggs
3. Butter

Result Example using indentation to create a hollow bullet point:
* Dairy
	* Milk
	* Cheese
* Protein
	* Eggs
	* Tofu
***

# Backslash escapes 
Use Backslash \ escapes to allow for literal characters which would otherwise have meaning in Markdown formatting syntax, example:

Syntax Example:  
\\*\*star\\*\*

Result Example:  

\*star\*

***

# Emojis
For emojis, use a colon : before and after.  

For example, using a colon before and after each of these:

 +1, tada, metal, sparkles

Results in these examples:
:+1: :tada: :metal: :sparkles:  

For more emojis check here:

[emoji cheat sheet](www.emoji-cheat-sheet.com)

***

# Image and Video

To insert an image, use an exclamation point before an image name in brackets and after that, the image link in parenthesis, like this: ![image name] (image link.jpg), 

Syntax Example:

\![xyz](https://github.com/Adam-p/markdown-here/raw/master/src/common/images/icon48.png

Result Example:
![xyz](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

To insert a video in Markdown, use the @ symbol before the title in brackets, followed by the video id embed code in parenthesis, like this: @[youtube] (video id), example:

\[youtube]\(http://www.youtube.com/embed/dQw4wgXcQ)

@[youtube](http://www.youtube.com/embed/dQw4w9WgXcQ)
***




