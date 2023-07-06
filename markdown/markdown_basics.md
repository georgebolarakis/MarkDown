
# Pragraph Examples

This  is my first paragraph example.

This is my second paragraph example

This example will feature a break
 about here but it will show up on
  this same line.

In this example, I will use a hard break  
to force a break here by  using two  
spaces at the end of a line.  
<!-- So we pressed the space twice after 'break', 'two' and 'line.' -->

# Header Examples

# Header 1
## Header 2  
### Header 3
#### Header 4
##### Header 5
###### Header 6


Also Header 1
=======

Also Header 2
-------


# Text Attributes Example

<!-- shwoing emphasis -->
<!-- for italics we add underscore at the beggingin and end of a word -->
In this first sentence, I will _really_ place *emphasis* on my words in two different ways.

Next I will write __very__, ****strong**** or bold text.

This example will contain an *intra* word emphasis. This is a varable name var_example_int but Markdown will render emphasis by default.

To escape an __underscore__ we need to **\_underscore**.

# Quotes Example

> Always remember that  you are absolutely unique.  
> Just like everyone else.   

>



##### _Margaret Mead_


# Code Exmples 

 >The `` is next to the left shift on it's own, if we shift it: ~, the four spaces do work at the begginging of the code snippet 

This `rm` command is used to delete files in Bash. For example:  


    cd ~
    ls -l
    rm myfile.txt
    # This is a comment
    var test = `test`

>We just backspace to get out of the codeblock

The `rm` command has many options, whch can be seen using `man rm`.

# List Examples

### Places to shop  
  
+ Supermarket
* Mall
- Gas Station

### States by population

1. California
1. Texas
1. Florida
1. New York
> we can add numbers infront of the names or just add one number and markdown will fix it for us.

### Favorite Foods (nested lists)
>We indent by two spaces and we add *

* Fruit
  * Wattermellon
  * Strawberies
* Veggies
  * Carrots


### Favorite Foods

1. Fruits are really good for you.  
   Get at least 1-2 servings in per day.
1. Vegies are great for vitamins and minerals.
   1. this list item contains a quote.
   >Here is a `

# Horizontal Rules Example #

Paragraph 1

---

Paragraph 2
***

Paragraph 3
___

# LInks Exapmles

One of the most popular search engines is google:  
[Google](https://google.com "Google Search")
> In the [] we add the name that we want to show, in the () we add the actual link  
> and in the "" we add the hover text.

A distant second is Microsoft's [Bing] [msb].  

> And we use the reference link above

>This is a reference link:  
[msb]: http://bing.com "Bing Engine"
> [msb] is the link Id, 'http://bing.com' is the web address, "Bing Engine" as the title.


  
  ### Websites
  <https://src.tips>

  ### Email

  <georgebolarakis@gmail.com>

  ----

  # Images Example

### Inline Images
This is a Line image:  
![Demo](http://placehold.it/350x150)

### Referenced Image
<!-- This doesn't work -->

![300x300 demo][Demo300]

Placehold.it is a nice place to get some placeholder graphics.
[Demo300]: http://placehold.it/300 "300-pixel squared placeholder"


# Inline HTML Example

Sometimes you need to add some inline HTML
 > Deffinition Lists

<dl>
    <dt>Markdown</dt>
    <dd>An awesome plain-text format</dd>
</dl>

### Here is the code for a definition list in HTML
    <dl>
    <dt>Markdown</dt>
    <dd>An awesome plain-text format</dd>
    </dl>





