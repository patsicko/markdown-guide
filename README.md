
# MARKDOWN SYNTAX GUIDE
##### By Patrick
## What is markdown?
Markdown is a lightweight markup language for creating formatted text using a plain-text editor. 
 Markdown is widely used in blogging, instant messaging, online forums, [collaborative software](https://en.wikipedia.org/wiki/Collaborative_software),documentation pages, and [readme files](https://en.wikipedia.org/wiki/README).

# Basic writing and formatting syntax

##  How to create Headings with Markdown

To create a heading, add one to six `#` symbols before your heading text. The number of `#` you use will determine the size of the heading.
`#` The largest heading
`##` The second largest heading
`######` The smallest heading

# The largest heading
## The second largest heading
###### The smallest heading

### Heading Best Practices
Markdown applications don’t agree on how to handle a missing space between the number signs (#) and the heading name. For compatibility, always put a space between the number signs and the heading name.



<br class="Apple-interchange-newline">

<h2 id="styling-text" style="box-sizing: border-box; margin-top: 24px; margin-bottom: 16px; font-weight: 600; font-size: 1.5em; line-height: 1.25; padding-bottom: 0.3em; border-bottom: 1px solid var(--color-border-muted); padding-top: 1rem; color: rgb(36, 41, 47); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;">Styling text</h2><p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 16px; color: rgb(36, 41, 47); font-family: -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, Helvetica, Arial, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;; font-size: 16px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;">You can indicate emphasis with bold, italic, strikethrough, subscript, or superscript text in comment fields and<span> </span><code style="box-sizing: border-box; font-family: ui-monospace, SFMono-Regular, &quot;SF Mono&quot;, Menlo, Consolas, &quot;Liberation Mono&quot;, monospace; font-size: 13.6px; padding: 0.2em 0.4em; margin: 0px; background-color: var(--color-neutral-muted); border-radius: 6px;">.md</code><span> </span>files.</p>

Style | Syntax | Keyboard shortcut | Example | Output
-- | -- | -- | -- | --
Bold | ** ** or __ __ | Command+B (Mac) or Ctrl+B (Windows/Linux) | **This is bold text** | This is bold text
Italic | * * or _ _ | Command+I (Mac) or Ctrl+I (Windows/Linux) | *This text is italicized* | This text is italicized
Strikethrough | ~~ ~~ |   | ~~This was mistaken text~~ | This was mistaken text
Bold and nested italic | ** ** and _ _ |   | **This text is _extremely_ important** | This text is extremely important
All bold and italic | *** *** |   | ***All this text is important*** | All this text is important

## Quoting code

You can call out code or a command within a sentence with single backticks. The text within the backticks will not be formatted. 

 Use \`git status` to list all new or modified files that haven't yet been committed.

#### output
Use `git status` to list all new or modified files that haven't yet been committed.
`


To format code or text into its own distinct block, use triple backticks.

Some basic Git commands are:
```
git status
git add
git commit
```

## Links
You can create an inline link by wrapping link text in brackets [ ], and then wrapping the URL in parentheses ( ).
    eg: `Consult [patsicko wiki on github for Markdown guide](https://github.com/patsicko/markdown-guide/wiki)`

output:

Consult [patsicko wiki on github for Markdown guide](https://github.com/patsicko/markdown-guide/wiki)

## Add an image

You can display an image by adding `!` and wrapping the alt text in `[ ]`. Then wrap the link for the image in parentheses `()`.

Here is an example
`![Patrick](https://pbs.twimg.com/media/FK-7LxOXMAArWL-.jpg)`

![Patrick](https://pbs.twimg.com/media/FK-7LxOXMAArWL-.jpg)

### Lists
**You can organize items into ordered and unordered lists.**

**Ordered Lists**
To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.
eg:

**Markdown**
1. First item
2. Second item
3. Third item
4. Fourth item`



**output**
1. First item
2. Second item
3. Third item
4. Fourth item



## Unordered Lists
To create an unordered list, add dashes `(-)`, asterisks `(*)`, or plus signs `(+)` in front of line items. Indent one or more items to create a nested list.

## URLs and Email Addresses
To quickly turn a URL or email address into a link, enclose it in angle brackets.
Eg:

`<https://github.com/patsicko/markdown-guide/wiki>`

`<patsicko@gmail.com>`
### output

<https://github.com/patsicko/markdown-guide/wiki>


<patsicko@gmail.com>


