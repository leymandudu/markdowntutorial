<!-- Headings -->
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6


<!-- ITLAICS: To make a text ITALIC, we can use asterick or underscore at the beginning and end of the text -->

*This text* is italic

_This text_ is italic


<!-- STRONG: To make a text STRONG, we can use double asterick or underscore at the beginning and end of the text -->

**This text** is BOLD

__This text__ is BOLD


<!-- STRIKETHROUGH: To make a text STRIKETHROUGH, we can use double TILDA at the beginning and end of the text -->

~~This text~~ is STRIKEDTHROUGH

<!-- HORIZONTAL RULE: To make an horizontal line, we can use either triple underscore or minus sign -->

---
___


<!-- BLOCKQUOTE: To make a BLOCKQUOTE, we can use a single greater than sign at the beginning of the text -->

> This is a quote

<!-- LINKS: To make a LINK, we will type our text inside a rectangle bracket and paste the corresponding link in a parenthesis. To give it a title, we include a quote inside the parenthesis-->

[Google](https://www.google.com "Google")


<!-- UNORDERED LIST: To create an unordered lists, we will use single asterick preceeding the text. Also, we can make a NESTED list by using TAB under the list we want to NEST. -->

* Item 1
* Item 2
    * Nested 1
        * Nested Nested 1
        * Nested Nested 2
    * Nested 2
* Item 3
* Item 4


<!-- ORDERED LIST: To create an ordered list, we will use number and dot preceeding the text. Also, we can created nested ordered list by using tab follow by number and dot and text -->

1. Item 1
1. Item 2
    1. Nested 1
    1. Nested 2
        1. Nested Nested 1
1. Item 3


<!-- INLINE CODE BLOCK: To create an inline code block, we will use back tick follow by the text/code -->

`<p>This is an inline code block</p>`


<!-- IMAGE: To create an image, we use bang sign follow by the image name in rectangular bracket and the URL in a parenthesis -->

![Markdown Logo](https://markdown-here.com/img/icon256.png)


<!-- Github Markdown -->

<!-- SYNTAX SPECIFIC CODE BLOCK: To create a syntax specific code block in Github, we will begin by using 3 MARK TICK at the beginning and end of the text including the environment we want our code to be written -->

<!-- For BASH SCRIPT -->

```bash

npm init

npm install

npm start

```


<!-- For JAVASCRIPT SCRIPT -->

```javascript
    function add(num1, num2) {
        return num1 + num2
    }
```


<!-- For PYTHON SCRIPT -->

```python
    def add(num1, num2):
        return num1 + num2
```


<!-- For TABLES -->

|  Name          |  Email                    |
|  ------------- |  -----------------------  |
|  John Doe      |  john@gmail.com           |
|  Mark Doe      |  mark@instagramonline.com |


<!-- For TASK LIST -->

* [x] Task 1
* [x] Task 2
* [ ] Task 3