##Bold Words
=============

##Header Indents
#Header1
##Header2
###Header3
####Header4
#####Header5
######Header6

##Multiple underscores in words

wow_great_stuff

do_this_and_do_that_and_another_thing.

##Paragraphs

On July 2, an alien mothership entered Earth's orbit and deployed several dozen saucer-shaped "destroyer" spacecraft, each 15 miles (24 km) wide.

On July 3, the Black Knights, a squadron of Marine Corps F/A-18 Hornets, participated in an assault on a destroyer near the city of Los Angeles.


##Blockquotes

In the words of Abraham Lincoln:

> Pardon my french

##Styling text

*This text will be italic*

**This text will be bold**

**Bold Text combined with  _italic text_ using stars and underscores**

##Code formatting

###Inline formats

Here's an idea: why don't we take `SuperiorProject` and turn it into `**Reasonable**Project`.

###Multiple lines

Check out this neat program I wrote:

```
x = 0
x = 2 + 2
what is x
```

##Links

###URL autolinking

http://example.com

###Link Text

[Visit GitHub!](https://www.github.com)

##Strikethrough

~~Mistaken text.~~

##Fenced code blocks

Here's an example:

```
function test() {
  console.log("notice the blank line before this function?");
}
```

##Syntax highlighting

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

##Tables

###Basic
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

###Aesthetic

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

###Non-Matching Dashes

| Name | Description          |
| ------------- | ----------- |
| Help      | Display the help window.|
| Close     | Closes a window     |

###Inline Markdown

| Name | Description          |
| ------------- | ----------- |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a window     |

###Alignment w/ Colons

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

##Lists
###Task Lists

####Basic

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> are supported
- [x] list syntax is required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

####Nested

- [ ] a bigger project
  - [ ] first subtask #1234
  - [ ] follow up subtask #4321
  - [ ] final subtask cc @mention
- [ ] a separate task

###Unordered lists

* Item
* Item
* Item

- Item
- Item
- Item

###Ordered lists

1. Item 1
2. Item 2
3. Item 3

###Nested lists

1. Item 1
  1. A corollary to the above item.
  2. Yet another point to consider.
2. Item 2
  * A corollary that does not need to be ordered.
    * This is indented four spaces, because it's two spaces further than the item above.
    * You might want to consider making a new list.
3. Item 3

##References

* SHA: a5c3785ed8d6a35868bc169f07e40e889087fd2e
* User@SHA: jlord@a5c3785ed8d6a35868bc169f07e40e889087fd2e
* User/Repository@SHA: jlord/sheetsee.js@a5c3785ed8d6a35868bc169f07e40e889087fd2e
* #Num: #26
* GH-Num: GH-26
* User#Num: jlord#26
* User/Repository#Num: jlord/sheetsee.js#26
