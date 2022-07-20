<!-- Comments can be written using Ctrl + /  -->
<!-- Markdown is used in two categories -->
<!-- 1) In General  -->
<!-- 1) For Git and Github -->

<!-- For Usual Use; -->


<!-- Headings are made as per in HTML; from h1 to h1 -->
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
<!-- Here Heading with one # will seem to be big and it gradually diminishes the size of Headings -->



#### Italic fonts in MD
<!-- Can be written in Italic Fonts if the letters  are written between *letters* or _letters -->
*Hello World* - This is in Italic Fonts
<!-- OR -->
_Hello World_ - Italic as well



#### Bold Letters
<!-- Bold letters can be written using double **letters** or __letters__ -->
**Hello World** - This is bold
<!-- OR -->
__Hello World__ - Bold as well



#### Strikethru fonts
<!-- ~~letters~~ is used to make StrikeThrough Fonts -->
~~Hello World~~ - Strikethrough texts




#### Code Blocks
<!-- Hrizontal Rules can be made by; -->
<!-- 1) By using ```letters``` -->
```
Hello World
```
#### Horizontal Rulers
<!-- 2) By using ___letters___ -->
___
Hello World
___




#### Blockquotes
<!-- Blockquotes can be written using > letters -->
> Hello World



### Embending Links
<!-- Links can be share like this [tab name](url) -->
[Pareidolia](https://en.wikipedia.org/wiki/Pareidolia)
<!-- To show title name on cursor; -->
[Pareidolia](https://en.wikipedia.org/wiki/Pareidolia "Pareidolia")




#### Unordered Lists
<!-- For Unordered Lists use * or - or - -->
<!-- On the page it will show Bold dot -->
* Sentence 1 or item 1 or Line 1
* Item 2
* Item 3
* Item 4
* Item 5
<!-- For nested items, will show with spaces -->
  * Item 1
  * Item 2
  * Item 3
  <!-- and so on -->





#### Ordered Lists
<!-- For Ordered Lists; use 1. for gradual numbers -->
1. Item 1
1. Item 2
1. Item 3
<!-- and so on -->






<!-- For Inline Blocks; Put blocks between '<title>' -->
'<p>This is a Paragraph</p>'



#### Linking Image Links
<!-- To show Images; use ![name](url) -->
![Markdown Logo](https://cdn.icon-icons.com/icons2/2699/PNG/512/markdown_here_logo_icon_169967.png)

<!-- Here it ends for general use; For Git and Github, it is almost similar thoo -->













<!-- For Github -->
#### Code blocks for GitHub(with lang.)
<!-- For code Blocks -->
```Bash
git fetch <url> <branch> && git merge FETCH_HEAD
```

<!-- Another example -->
```javascript
  function add(num1, num2) {
      return num1 + num2;
  }
```



#### Make Tables
<!-- For making tables -->
| Names       |  Email                       |
| ----------- | ---------------------------  |
| ritukanta   | reddyritukanta1925@gmail.com |
| so on       | so.on@gmail.com              |


#### Task Lists
<!-- For Task Lists -->
* [x] Task 1
* [x] Task 2
* [ ] Task 3






<!-- Extra stuff -->
#### Author Names
<!-- Attach contributor or author names -->
<cite>ritukanta</cite>


#### Separated letters
<!-- For code blocks for certain words or letters -->
<code>Hello World</code>





#### For HTML Tags (</>)
<!-- For code blocking words used in </> format -->
<!-- These are can not be written using <code>...</code> simply -->
<code>&lt;div&gt;</code>
<!-- The above will the word "div" as <div> -->
<!-- To show </div>; -->
<code>&lt;/div&gt;</code>



#### Blockquotes under Blockquotes
<!-- For Blockquotes under other Blockquotes -->
> Hello World ~
>> Hello World +


#### Re-direct to Headlines
<!-- To link headers or headings in README -->
<!-- Use [Name](#heading name with no spaces but with -) -->
<!-- Lemme link the heading no.3 below -->
* [Heading 3](#heading-3)
<!-- This will create a link to heading no.3 -->
<!-- This helps  a lot in linking certain headings-->




#### Link Local Images
<!-- For showing Local images; -->
<!-- As I've images folder and images inside it -->
![Husky Pup](../images/husky.jpg)
![Golden Retriever](../images/golden-retriever.jpg)

<!-- We can add external links thru these local images -->
<!-- By clicking the images, external links can be browsed; -->
[![Husky](../images/husky.jpg)](https://en.wikipedia.org/wiki/Husky)




#### Some HTML tags can be used
<!-- <br> tag is used to separate lines -->
Huskies<br>Golden Retrievers

* p tags
* img tags
* h1-h3 tags
> However using HTML Tags in Markdown ain't a standard practice <br>
<code>&lt;/&gt;</code>