---
layout: blog
category: blog
published: true
splash: "http://placehold.it/1600x500"
title: Sample Markdown Content
---

# Basic content style test page

This page is designed to stress test the basic content styles for this theme, starting with the default font for displaying text. This first section is wrapped in a p tag.

<div>This section of text is not wrapped in a <code>p</code> tag — just a plain <code>div</code> tag. Compare the style of this text with the text above. Pay attention to any differences in font-family, font-style, font-weight, font-size, line-spacing, letter-spacing, etc. If it looks different from the preceding paragraph in any way you should know the reason why. Because it is wrapped in a div, this section of text should not contain any default margin or padding. </div>

## Level 2 content heading

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 

[Duis aute irure dolor]() in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. [Excepteur]() sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Level 3 content heading

Here are some simple bullet lists, without inner `<p>` tags.

--- 

#### Unordered list

- Unordered list item
- Unordered list item with a nested list
    - Nested unordered list item
    - Nested unordered list item
- Unordered list item
- Unordered list item

#### Ordered list

1. Ordered list item
2. Ordered list item with a nested list
    1. Ordered list item
    2. Ordered list item
3. Ordered list item
4. Ordered list item

#### Horizontal Rule

Here is an example of a horizontal rule

---

In HTML5 the HTML `<hr>` element represents a thematic break between paragraph-level elements (for example, a change of scene in a story, or a shift of topic with a section). In previous versions of HTML, it represented a horizontal rule. It may still be displayed as a horizontal rule in visual browsers, but is now defined in semantic terms, rather than presentational terms.


#### Preformatted Text

Typically displayed in a non-proportional font exactly as it is laid out in the file. Whitespaces inside this element are displayed as typed.

    <div class="code-example">
        <h2>This is some example code</h2>
        <p>It should serve as an example.</p>
    </div>


#### Block Quote
> Indicates that the enclosed text is an extended quotation. Usually, this is rendered visually by indentation (see Notes for how to change it). A URL for the source of the quotation may be given using the cite attribute, while a text representation of the source can be given using the `cite` element.


#### Images

Here are some images marked up in a few different ways. This first example uses Markdown syntax like 

```
    ![Alt text](/path/to/img.jpg "Optional title")
```
---

![This is a proper figure + figcaption - Multi-Markdown.](https://www.evernote.com/shard/s2/sh/1487e052-b23e-41b0-a0d3-751c0b74d87c/4bf7443ec0fe857873ce9f2285095b47/deep/0/Fullscreen%202013-05-12%208:38%20PM.png)  



    ![This is a proper figure + figcaption - Multi-Markdown.](https://www.evernote.com/shard/s2/sh/1487e052-b23e-41b0-a0d3-751c0b74d87c/4bf7443ec0fe857873ce9f2285095b47/deep/0/Fullscreen%202013-05-12%208:38%20PM.png)



The following example uses an HTML `<img>` tag, followed by a markdown style line break, followed by a span of italic text:

<img src="https://www.evernote.com/shard/s2/sh/1487e052-b23e-41b0-a0d3-751c0b74d87c/4bf7443ec0fe857873ce9f2285095b47/deep/0/Fullscreen%202013-05-12%208:38%20PM.png">  
_This is an implied caption._

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.


#### Tables

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3



