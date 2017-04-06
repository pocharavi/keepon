---
layout: default
title: Learning markdown
date: 06-04-2017
tag: Markdown
---
Learning markdown
=======

Hi everyone today I am going to share the experience on learning markdown.

My first encounter with markdown is at gitlab website. One day I wrote README file on the website without markdown. Afer I commit I saw plain text without any styles except blockquote. After that, I saw md file extension. So I started searching and get excited to learn it.

What is Markdown?
---------------
Markdown is a lightweight markup language that basically translates into HTML. Markdown is commonly used to write information about projects on Github, gitlab, and bitbucket etc. Markdown is also widely used in note taking because of its flexibility. Markdown is also useful to write static sites like this one. Note taking with markdown is very interesting, easy and fun. Markdown extension is .md.

Diving into Markdown
----------------

Now we are entering into writing markdown.

First, start with headings.

~~~

#h1 heading
##h2 heading 
###h3 heading
######h6 heading

h1
==========

h2
-----------
~~~

# h1 heading
## h2 heading 
### h3 heading
###### h6 heading



>Blank empty line is Paragraph.

~~~
/** This is bold/**                   This is bold text
/__ This is also bold/__              This is also bold text

/*This is italic/*                    Italic
/_This is also italic/_               Italic

~~~

__This is also bold__              

*This is italic*                    

~~~

>blockquotes are start with this
> > This is nested blockquote

~~~
>blockquotes are start with this
> > This is nested blockquote



Lists

~~~
Ordered lists

1. list item
2. list item
3. list item

Unordered list
* list item
* list item
* list item

~~~
Ordered lists

1. list item
2. list item
3. list item

Unordered list
* list item
* list item
* list item



Tables

~~~
header1    | header2
-----------|-----------
cell1      | cell2

~~~

header1    | header2
-----------|-----------
cell1      | cell2


To create a block of text and programming snippets to show use use ~~~   ~~~ this bloc and defien the programming language at start of the tild symbols.
~~~javascript
    ~~~javascript
    console.log("hello markdown")
    ~~~
~~~


Links

~~~

[Google](https:/google.com)       web link

Images

![text](link)

[text](link)               page link

~~~

[Google](https:/google.com)       web link


For checklist
~~~

-[] uncompleted task
-[X] completed task

~~~

>You can use HTML tags in the middle of markdown.
You can use <del></del> tag to line through the text. 

>Markdown is different from different sources.

>For more go to [Daring Fireball](https://daringfireball.net/).

>The main problem when writing makdown is syntax. Even one single space make a lot of difference. Main place is defining lists.



















