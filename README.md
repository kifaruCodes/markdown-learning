# **Markdown Learning**
This is a personal quick-guide/reference on using Markdown.
This is meant to help me refresh my knowledge on md

I will mostly be using it in my git readme documentation amongst other applications



# The documentation

## Headings
---
---
You can put headings by using the '#' symbol before a title heading.
The more '#' you put the lower the headings get

ie 
- # This is a H1 heading with one '#'
- ## This is a H2 heading with two '#'
- ### This is a H3 heading with three '#'
- #### This is a H4 heading with four '#'
- ##### This is a H5 heading with five '#'

## Text formatting
---
---
You can put text in bold and italics, but you can not underline text in markdown.

- For **Bold** text, put your text betwen a pair of double asterisk'\*\*' signs, ie '\*\*Text\*\*' will be rendered as **Text**
- For *Italics* put your text betwen a pair of single asterisk'\*' signs, ie '\*Text\*' will be rendered as *Text*
- For both ***Bold and Italics*** put your text betwen a pair of tripple asterisk'\*' signs, ie '\*\*\*Text\*\*\*' will be rendered as ***Text***


## Ordered and Unordered list
---
---
To put **unordered** lists, put a '-' before your list sentences, while for **ordered** lists, put a number before your list sentences.

Example of unordered list:
- one 
- two
- three

Example of ordered list:
1. one
2. two
3. three

## Images and Links
---
---
The formatting used for images and links are almost identical with one slight difference:

- Images : \[alt text](image url)
- Link : \![Link text](Link Url)



## Code formatting
---
---
Code formatting can be done in two ways:
- In-line code formatting
- Block code formatting

With inline, the code statement is encapsulated in single back-ticks. This is good for one liners.

**\`code statement`** renders as 

`System.out.println("Hello World")`



With blocks of code, one can encapsulate the code block in three back-ticks as below

```
public class Main {
    public static void main(String[] args) {
        System.out.print("Hello there");   
    }
}
```

For syntax highlighting one can add the language after the first backticks 

```java
public class Main {
    public static void main(String[] args) {
        System.out.print("Hello there");   
    }
}
```
