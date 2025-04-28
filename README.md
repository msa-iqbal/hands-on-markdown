# Hands-on Markdown

🙂 Welcome to **Hands-on Markdown!**  
This repository is a practical guide and playground for mastering **Markdown syntax** — the lightweight and powerful markup language that's essential for writing clean documentation, README files, wikis, blogs, and more.

## Table of Contents

1. [Headings](#headings)
2. [Bold](#bold)
3. [Italic](#italic)
4. [Bold & Italic](#bold--italic)
5. [Line Breaks](#line-breaks)
6. [Strikethrough](#strikethrough)
7. [Underline](#underline)
8. [Highlight](#highlight)
9. [Comments](#comments)
10. [Blockquote](#blockquote)
11. [Ordered List](#ordered-list)
12. [Unordered List](#unordered-list)
13. [Code](#code)
14. [Horizontal Rule](#horizontal-rule)
15. [Link](#link)
16. [Image](#image)
17. [Table](#table)
18. [Code Block](#code-block)
19. [Heading ID](#heading-id)
20. [Task List](#task-list)
21. [Symbols](#symbols)
22. [Emoji](#emoji)
23. [Mathematical Expressions](#mathematical-expressions)
24. [Diagrams](#diagrams)
25. [Dropdown](#dropdown)
26. [Image Based on Theme](#image-based-on-theme-lightdark)
27. [Embed YouTube Video](#embed-youtube-video)
28. [Escaping Characters](#escaping-characters)
29. [HTML in Markdown](#html-in-markdown)
30. [Footnotes](#footnotes)

## Headings

**Example:**

```markdown
# H1 - Heading 1

## H2 - Heading 2

### H3 - Heading 3

#### H4 - Heading 4

##### H5 - Heading 5

###### H6 - Heading 6
```

**Output:**

# H1 - Heading 1

## H2 - Heading 2

### H3 - Heading 3

#### H4 - Heading 4

##### H5 - Heading 5

###### H6 - Heading 6

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Bold

**Example:**

```markdown
**Bold Text**
```

**Output:**

**Bold Text**

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Italic

**Example:**

```markdown
_Italic Text_
```

**Output:**

_Italic Text_

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Bold & Italic

**Example:**

```markdown
_**Bold and Italic Text**_
```

**Output:**

_**Bold and Italic Text**_

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Line Breaks

In Markdown, to create a line break, add two or more spaces at the end of a line and then press `Enter`. Alternatively, you can insert an explicit `<br>` tag where you want the line to break.

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Strikethrough

It adds a horizontal line through the text.

**Example:**

```markdown
~~This text will be strikethrough~~
```

**Output:**

~~This text will be strikethrough~~

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Underline

Standard Markdown does not natively support underlining. However, you can simulate underlining by using HTML tags within your Markdown content.

**Example:**

```markdown
Here is some normal text, and <u>here is underlined text</u> inside the same line.
```

**Output:**

Here is some normal text, and <u>here is underlined text</u> inside the same line.

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Highlight

Markdown itself does not have built-in Example for highlighting text. However, you can simulate highlighting in Markdown by using HTML tags, such as `<mark>`.

**Example:**

```markdown
This is <mark>highlighted</mark> text.
```

**Output:**

This is <mark>highlighted</mark> text.

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Comments

In Markdown, there’s no native comment Example, but you can safely use HTML comments, and they will not appear when the Markdown is rendered.

**Example:**

```markdown
Markdown makes docs <!-- and life --> easier.
```

**Output:**

Markdown makes docs <!-- and life --> easier.

<!-- START "Jump to Top" -->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Blockquote

**Example (Basic):**

```markdown
> Blockquote
```

**Output:**

> Blockquote

**Example (Nested Blockquotes):**

```markdown
> This is a first-level blockquote.
>
> > This is a second-level (nested) blockquote.
> >
> > > This is a third-level (deeply nested) blockquote.
>
> Back to first-level blockquote.
```

**Output:**

> This is a first-level blockquote.
>
> > This is a second-level (nested) blockquote.
> >
> > > This is a third-level (deeply nested) blockquote.
>
> Back to first-level blockquote.

**Example (Blockquotes with Other Elements):**

````markdown
> To print in JavaScript
>
> ```javascript
> console.log("Hello, Always Smile!");
> ```
````

**Output:**

> ### To print in JavaScript
>
> ```javascript
> console.log("Hello, Always Smile!");
> ```

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Ordered List

**Example (Basic):**

```markdown
1. First item
1. Second item
1. Third item
```

**Output:**

1. First item
1. Second item
1. Third item

**Example (Nested Order List):**

```markdown
1. First item
   1. First nested item
   2. Second nested item
2. Second item
   1. First nested item
      1. Deeply nested item
3. Third item
```

**Output:**

1. First item
   1. First nested item
   2. Second nested item
2. Second item
   1. First nested item
      1. Deeply nested item
3. Third item

💡 Note: Numbers auto-fix, formatting (bold, italic, links) allowed, indent 4 spaces for sublists.

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Unordered List

**Example (Basic):**

```markdown
- Apple
- Banana
- Cherry
```

**Output:**

- Apple
- Banana
- Cherry

**Example (Nested Unordered List):**

```markdown
1. Frontend
   - HTML
   - CSS
     - Flexbox
     - Grid
   - JavaScript
1. Backend
   - Node.js
   - Express.js
```

**Output:**

1. Frontend
   - HTML
   - CSS
     - Flexbox
     - Grid
   - JavaScript
1. Backend
   - Node.js
   - Express.js

💡 Note: Numbers auto-fix, formatting (bold, italic, links) allowed, indent 4 spaces for sublists.

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Code

**Example:**

```
To declare a variable in JavaScript, use `let` or `const`.
```

**Output:**

To declare a variable in JavaScript, use `let` or `const`.

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Horizontal Rule

You can create a horizontal rule by using three or more dashes (`---`), asterisks (`***`), or underscores (`___`), each on its own line. Using `---` is preferred for a clean, professional appearance and aligns with GitHub-flavored Markdown standards; therefore, it is the recommended practice.

**Example:**

```markdown
---
```

**Output:**

---

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Link

**Example (Basic):**

```markdown
[My Drive](https://www.flickr.com/photos/spnkhn/albums/)
```

**Output:**

[My Drive](https://www.flickr.com/photos/spnkhn/albums/)

**Example (Adding Title):**

```markdown
[My Drive](https://www.flickr.com/photos/spnkhn/albums/ "You're Welcome!")
```

**Output:**

[My Drive](https://www.flickr.com/photos/spnkhn/albums/ "You're Welcome!")

**Example (Link with Inline Code):**

```markdown
[`My Drive`](https://www.flickr.com/photos/spnkhn/albums/ "You're Welcome!")
```

**Output:**

[`My Drive`](https://www.flickr.com/photos/spnkhn/albums/ "You're Welcome!")

**Example (Open a Link in a New Tab):**

```markdown
<a href="https://www.flickr.com/photos/spnkhn/albums/" target="_blank">My Drive</a>
```

**Output:**

<a href="https://www.flickr.com/photos/spnkhn/albums/" target="_blank">My Drive</a>

💡 Tips: When you paste a full URL (like `https://example.com`) directly into a Markdown file without any special Example, most Markdown renderers will automatically turn it into a clickable link.

You don't need to manually wrap it inside `[text](url)` unless you want custom text.

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Image

**Example (Basic):**

```markdown
![Island](https://cdn.pixabay.com/photo/2022/05/31/07/01/island-7232868_1280.png)
```

**Output:**

![Island](https://cdn.pixabay.com/photo/2022/05/31/07/01/island-7232868_1280.png)

**Example (Image with Optional Title):**

```markdown
![Nature](./assets/images/view.jpg "My favourite place!")
```

**Output:**

![Nature](./assets/images/view.jpg "My favourite place!")

**Example (Image with Link):**

```markdown
[![Signature](./assets/images/signature.png)](https://www.flickr.com/photos/spnkhn/albums/)
```

**Output:**

[![My Drive](./assets/images/signature.png)](https://www.flickr.com/photos/spnkhn/albums/)

**Example (Image Captions):**

Markdown alone doesn’t officially support visible image captions. But there are several **smart workarounds** using **HTML** inside Markdown.

```html
<figure align="right">
  <img
    src="./assets/images/late-afternoon.jpg"
    alt="Late Afternoon"
    width="80%"
  />
  <figcaption>
    Late afternoon is the day's gentle reminder that even endings can be
    beautiful
  </figcaption>
</figure>
```

**Output:**

<figure align="right">
    <img src="./assets/images/late-afternoon.jpg"
         alt="Late Afternoon" width="80%"  >
    <figcaption>Late afternoon is the day's gentle reminder that even endings can be beautiful</figcaption>
</figure>

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Table

**Example (Basic):**

```markdown
| Header 1 | Header 2 | Header 3 |
| -------- | -------- | -------- |
| Data 1   | Data 2   | Data 3   |
| Data 4   | Data 5   | Data 6   |
```

**Use to:**

- `|` (pipe) - Separates columns
- `-` (dash) - Separates header from body

**Output:**

| Header 1 | Header 2 | Header 3 |
| -------- | -------- | -------- |
| Data 1   | Data 2   | Data 3   |
| Data 4   | Data 5   | Data 6   |

**Example (Column Alignment):**

```markdown
| Left Align | Center Align | Right Align |
| :--------- | :----------: | ----------: |
| Apple      |    Orange    |      Banana |
| Cherry     |    Mango     |      Carrot |
```

**Use to:**

- `:---` - Left align
- `:---:` - Center align
- `---:` - Right align

**Output:**

| Left Align | Center Align | Right Align |
| :--------- | :----------: | ----------: |
| Apple      |    Orange    |      Banana |
| Cherry     |    Mango     |      Carrot |

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Code Block

**Example:**

````
``` <preferred_language>
    ---
       Your Code ...
           ---
    ---
```
````

💡 Note: For Example highlighting, specify the language immediately after the first set of triple backticks. If no Example highlighting is required, use `markdown` after the triple backticks _(recommended)_.

**Example:**

````
```javascript
const emojis = ["😀", "🎉", "🚀", "🌈", "🍕", "🐶", "🌟"];

function getRandomEmoji() {
  const randomIndex = Math.floor(Math.random() * emojis.length);
  return emojis[randomIndex];
}

// Example usage:
console.log("Your random emoji is:", getRandomEmoji());

```
````

**Output:**

```javascript
const emojis = ["😀", "🎉", "🚀", "🌈", "🍕", "🐶", "🌟"];

function getRandomEmoji() {
  const randomIndex = Math.floor(Math.random() * emojis.length);
  return emojis[randomIndex];
}

// Example usage:
console.log("Your random emoji is:", getRandomEmoji());
```

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Heading ID

If you want to link to another part of the same Markdown file (like a heading), you can do it like this:

Example if your heading is:

```markdown
## Introduction

Welcome to the project!

## Features & Benefits

This section describes features.

## What's New?

All new updates listed here.

### Subsection: Updates

Detailed minor updates.
```

You can link to it like:

```markdown
[Introduction](#introduction)
[Go to Features](#features--benefits)
[See What's New](#whats-new)
[Minor Updates](#subsection-updates)
```

It automatically gets an ID by:

- Converting all letters to lowercase,
- Replacing spaces with hyphens (-),
- Removing special characters (like punctuation).

- Example
  - `## Introduction` - Auto-Generated ID is - `#introduction`
  - `## Features & Benefits` - Auto-Generated ID is - `#features--benefits`
  - `## What's New?` - Auto-Generated ID is - `#whats-new`
  - `Subsection: Updates` - Auto-Generated ID is - `#subsection-updates`

**Output:**

## Introduction

Welcome to the project!

## Features & Benefits

This section describes features.

## What's New?

All new updates listed here.

### Subsection: Updates

Detailed minor updates.

[Introduction](#introduction)  
[Go to Features](#features--benefits)  
[See What's New](#whats-new)  
[Minor Updates](#subsection-updates)

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Task List

A task list lets you create checkboxes (☑ / ⏹) in Markdown.

**Use to:**

- [ ] for unchecked tasks (a blank space inside the brackets).

- [x] for checked tasks (lowercase "x" inside the brackets).

**Example:**

```markdown
### :memo: To-Do List

- [ ] Learn Markdown basics
- [x] Set up GitHub repository
- [ ] Create README.md
- [x] Push first commit
```

**Output:**

### :memo: To-Do List

- [ ] Learn Markdown basics
- [x] Set up GitHub repository
- [ ] Create README.md
- [x] Push first commit

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Symbols

Markdown does not include dedicated syntax for special symbols. However, in most cases, you can simply copy and paste the desired **Symbol** directly into your Markdown document.

In Markdown, symbols usually mean:

- Special characters (©, →, ★, ✓)

- Emoji shortcodes (`:smile:`, 😄)

- HTML entities (`&copy;`, `&rarr;`)

### Method 1: Direct Unicode Characters

```markdown
© 2025 Your Company
```

**Output:**

© 2025 Your Company

### Method 2: Using HTML Entities

You can insert special symbols using HTML entities:

| Symbol               | Code       | Output   |
| :------------------- | :--------- | :------- |
| Copyright            | `&copy;`   | &copy;   |
| Registered trademark | `&reg;`    | &reg;    |
| Trademark            | `&trade;`  | &trade;  |
| Arrow Left           | `&larr;`   | &larr;   |
| Arrow Up             | `&uarr;`   | &uarr;   |
| Arrow Right          | `&rarr;`   | &rarr;   |
| Arrow Down           | `&darr;`   | &darr;   |
| Degree               | `&#176;`   | &#176;   |
| Pi                   | `&#960;`   | &#960;   |
| Heart                | `&hearts;` | &hearts; |
| Check Mark (tick)    | `&#10003;` | &#10003; |
| Cross mark (wrong)   | `&#10007;` | &#10007; |
| En Dash (medium)     | `&ndash;`  | &ndash;  |
| Em Dash (long)       | `&mdash;`  | &mdash;  |

**Example:**

```markdown
&copy; 2025 MyWebsite &mdash; All rights reserved.
```

**Output:**

&copy; 2025 MyWebsite &mdash; All rights reserved.

### Method 3: Using Emoji Shortcodes (Platform Specific)

On platforms like GitHub, you can use emoji shortcodes:

**Example:**

```markdown
:smile: :rocket: :heart: :star:
```

**Output:**

:smile: :rocket: :heart: :star:

💡 Tips: Use HTML entities (`&copy;`, `&rarr;`, etc) if you want maximum compatibility across different Markdown renderers.

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Emoji

Emojis are small icons used to make Markdown documents more expressive and fun. They improve readability, highlight important parts, and add personality to your text!

**Example (Directly Copy-Paste Emoji):**

```markdown
I love coding! ☕
```

**Output:**

I love coding! ☕

**Example (GitHub-Style Emoji Shortcodes):**

```markdown
I love coding! :coffee:
```

**Output:**

I love coding! :coffee:

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Mathematical Expressions

In Markdown, you can display **mathematical expressions** using a combination of **inline HTML** and **MathJax** (or other rendering libraries like KaTeX). Markdown itself doesn’t directly support rendering mathematical formulas, but platforms like **GitHub**, **GitLab**, and others that use **MathJax** can interpret these formulas.

Here's a guide to writing **mathematical expressions** in Markdown:

### **Using LaTeX Example with MathJax/KaTeX**

Markdown doesn’t natively support **LaTeX** math rendering, but on platforms that support MathJax or KaTeX, you can write math expressions using **LaTeX Example**.

#### Inline Math

Use **`$`** to wrap inline math expressions. For Example:

```latex
The formula for the area of a circle is $A = \pi r^2$.

The formula for water is $ \text{H}_2\text{O} $.
```

Output:

The formula for the area of a circle is $A = \pi r^2$.

The formula for water is $\text{H}\_2\text{O} $

#### Display Math

Use **`$$`** for display math (equations centered on their own line). For Example:

```latex
$$
E = mc^2
$$
```

Output:

$$
E = mc^2
$$

### **Supported Operators and Functions**

You can use the following **LaTeX math operators** within Markdown:

- **Superscript and Subscript**: `x^2` for superscript, `x_1` for subscript
- **Fractions**: `\frac{a}{b}`
- **Sums and integrals**: `\sum`, `\int`
- **Square root**: `\sqrt{x}`
- **Greek letters**: `\alpha`, `\beta`, `\gamma`, etc.
- **Trigonometric functions**: `\sin`, `\cos`, `\tan`
- **Mathematical symbols**: `\pi`, `\infty`, `\geq`

Example: Complex Math Expression

```latex
$$
\int_{0}^{\infty} \frac{1}{x^2 + 1} dx = \frac{\pi}{2}
$$
```

Output:

$$
\int_{0}^{\infty} \frac{1}{x^2 + 1} dx = \frac{\pi}{2}
$$

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Diagrams

In Markdown, creating diagrams can be done with several tools, but Markdown itself doesn’t directly support **drawing diagrams.**

However, there are some creative ways to embed diagrams using external tools or images.

### Method 1: Embed Diagrams as Images

The simplest method is to create the diagram with an external tool (e.g., draw.io, Lucidchart, or any diagram tool), save it as an image (PNG, JPG, etc.), and embed it in your Markdown file.

**Example:**

```markdown
![Git and GitHub Workflow](./assets/images/diagram-tr.png)
```

**Output:**

![Git and GitHub Workflow](./assets/images/diagram-tr.png)

### Method 2: Using Mermaid Diagrams (GitHub Flavored Markdown)

GitHub Flavored Markdown supports **Mermaid diagrams**, which allows you to draw **flowcharts, sequence diagrams, class diagrams,** etc., using simple text Example.

💡 Note:

- You need to make sure the platform you're using (like GitHub, GitLab, or a Markdown editor) supports Mermaid diagrams to render them properly.

- If you are working with Mermaid diagrams in VSCode, it is recommended to install the **Mermaid** official extension.

Mermaid code is written inside code blocks using the `mermaid` keyword, and the diagrams are rendered by supported platforms.

````markdown
```mermaid
<your mermaid diagram code here>
```
````

**Example (Flow Chart):**

- `TD` → Top Down

- `LR` → Left to Right

- `RL` → Right to Left

- `BT` → Bottom to Top

````markdown
```mermaid
flowchart LR
  A[Start] --> B[Process] --> C[End]
```
````

**Output:**

```mermaid
flowchart LR
  A[Start] --> B[Process] --> C[End]
```

**Example (Gantt Chart):**

````markdown
```mermaid
gantt
    title School Website Development Timeline
    dateFormat  YYYY-MM-DD
    section Planning
    Requirement Gathering       :done,     plan1, 2025-05-01, 5d
    Define Features and Pages    :done,     plan2, 2025-05-06, 3d
    Create Project Plan          :active,   plan3, 2025-05-09, 3d

    section Design
    Design Wireframes            :          design1, 2025-05-12, 5d
    Finalize UI/UX Design         :          design2, 2025-05-17, 4d

    section Development
    Setup Hosting & Domain       :          dev1, 2025-05-21, 2d
    Frontend Development (HTML/CSS/JS) :     dev2, 2025-05-23, 10d
    Backend Development (Admin Panel, DB) : dev3, 2025-05-28, 10d
    CMS Integration (if any)      :          dev4, 2025-06-02, 5d

    section Content Creation
    Prepare School Content       :          content1, 2025-06-03, 5d
    Add Photos, Events, News      :          content2, 2025-06-08, 3d

    section Testing
    Functional Testing           :          test1, 2025-06-11, 3d
    Browser & Mobile Testing      :          test2, 2025-06-14, 2d
    Fix Bugs                      :          test3, 2025-06-16, 3d

    section Launch
    Final Review                  :          launch1, 2025-06-19, 2d
    Go Live!                      :milestone, launch2, 2025-06-21, 0d
    Post-launch Monitoring        :          post1, 2025-06-22, 5d
```
````

**Output:**

```mermaid
gantt
    title School Website Development Timeline
    dateFormat  YYYY-MM-DD
    section Planning
    Requirement Gathering       :done,     plan1, 2025-05-01, 5d
    Define Features and Pages    :done,     plan2, 2025-05-06, 3d
    Create Project Plan          :active,   plan3, 2025-05-09, 3d

    section Design
    Design Wireframes            :          design1, 2025-05-12, 5d
    Finalize UI/UX Design         :          design2, 2025-05-17, 4d

    section Development
    Setup Hosting & Domain       :          dev1, 2025-05-21, 2d
    Frontend Development (HTML/CSS/JS) :     dev2, 2025-05-23, 10d
    Backend Development (Admin Panel, DB) : dev3, 2025-05-28, 10d
    CMS Integration (if any)      :          dev4, 2025-06-02, 5d

    section Content Creation
    Prepare School Content       :          content1, 2025-06-03, 5d
    Add Photos, Events, News      :          content2, 2025-06-08, 3d

    section Testing
    Functional Testing           :          test1, 2025-06-11, 3d
    Browser & Mobile Testing      :          test2, 2025-06-14, 2d
    Fix Bugs                      :          test3, 2025-06-16, 3d

    section Launch
    Final Review                  :          launch1, 2025-06-19, 2d
    Go Live!                      :milestone, launch2, 2025-06-21, 0d
    Post-launch Monitoring        :          post1, 2025-06-22, 5d
```

**Example (Timeline Chart):**

````markdown
```mermaid
timeline
    title School Website - Simple Timeline
    2025-05-01 : Planning Started
    2025-05-10 : Designing Started
    2025-05-20 : Development Started
    2025-06-10 : Testing Started
    2025-06-21 : Website Launched
```
````

**Output:**

```mermaid
timeline
    title School Website - Simple Timeline
    2025-05-01 : Planning Started
    2025-05-10 : Designing Started
    2025-05-20 : Development Started
    2025-06-10 : Testing Started
    2025-06-21 : Website Launched
```

**Example (Pie Chart):**

````markdown
```mermaid
pie title Daily Mobile App Usage
    "Social Media" : 45
    "Entertainment" : 20
    "Productivity" : 15
    "Games" : 10
    "Health & Fitness" : 5
    "Other" : 5
```
````

**Output:**

```mermaid
pie title Daily Mobile App Usage
    "Social Media" : 45
    "Entertainment" : 20
    "Productivity" : 15
    "Games" : 10
    "Health & Fitness" : 5
    "Other" : 5
```

**Example (Mind-Map Diagram):**

````markdown
```mermaid
mindmap
  root((Project))
    Planning
      Requirements
      Timeline
      Budget
    Design
      Wireframes
      UI Design
    Development
      Frontend
        HTML
        CSS
        JavaScript
      Backend
        Node.js
        Database
    Testing
      Unit Tests
      Integration Tests
    Deployment
      Production Server
      Monitoring
```
````

**Output:**

```mermaid
mindmap
  root((Project))
    Planning
      Requirements
      Timeline
      Budget
    Design
      Wireframes
      UI Design
    Development
      Frontend
        HTML
        CSS
        JavaScript
      Backend
        Node.js
        Database
    Testing
      Unit Tests
      Integration Tests
    Deployment
      Production Server
      Monitoring
```

**Example (Git-Graph Diagram):**

````markdown
```mermaid
gitGraph
   commit id: "Initial commit"
   commit id: "Set up project structure"
   branch feature/login
   checkout feature/login
   commit id: "Create login page"
   commit id: "Add login validation"
   checkout main
   commit id: "Add homepage"
   merge feature/login id: "Merge login feature"
   branch feature/cart
   checkout feature/cart
   commit id: "Implement shopping cart"
   checkout main
   merge feature/cart id: "Merge cart feature"
```
````

**Output:**

```mermaid
gitGraph
   commit id: "Initial commit"
   commit id: "Set up project structure"
   branch feature/login
   checkout feature/login
   commit id: "Create login page"
   commit id: "Add login validation"
   checkout main
   commit id: "Add homepage"
   merge feature/login id: "Merge login feature"
   branch feature/cart
   checkout feature/cart
   commit id: "Implement shopping cart"
   checkout main
   merge feature/cart id: "Merge cart feature"
```

**Example (State Diagram):**

````markdown
```mermaid
stateDiagram-v2
    [*] --> Idle
    Idle --> Planning : Start New Project
    Planning --> Designing : Approve Requirements
    Designing --> Developing : Finalize UI/UX
    Developing --> Testing : Complete Features ✔️
    Testing --> Deployment : Pass QA
    Deployment --> [*] : Launch Successfully 🎉
    Testing --> Developing : Found Bugs 🐞
    note right of Testing
      Testing includes:
      - Functional Testing
      - UI/UX Testing
      - Performance Testing
    end note
```
````

**Output:**

```mermaid
stateDiagram-v2
    [*] --> Idle
    Idle --> Planning : Start New Project
    Planning --> Designing : Approve Requirements
    Designing --> Developing : Finalize UI/UX
    Developing --> Testing : Complete Features ✔️
    Testing --> Deployment : Pass QA
    Deployment --> [*] : Launch Successfully 🎉
    Testing --> Developing : Found Bugs 🐞
    note right of Testing
      Testing includes:
      - Functional Testing
      - UI/UX Testing
      - Performance Testing
    end note
```

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Dropdown

In pure Markdown, there is no built-in support for creating dropdowns (collapsible sections).
However, you can achieve dropdown-like (collapsible) behavior using HTML `<details>` and `<summary>` tags, which are supported on platforms like GitHub, GitLab, and others that allow HTML inside Markdown.

**Example (In HTML):**

```markdown
<details>
  <summary>Click to expand</summary>

Content inside the dropdown.

</details>
```

**Example:**

```markdown
<details>
  <summary>See More Details</summary>

Here is some hidden content that only appears when you click the dropdown!

- Point 1
- Point 2
- **Bold Content**
- [Link to somewhere](https://example.com)

</details>
```

**Output:**

<details>
  <summary>See More Details</summary>

Here is some hidden content that only appears when you click the dropdown!

- Point 1
- Point 2
- **Bold Content**
- [Link to somewhere](https://example.com)

</details>

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Image Based on Theme (Light/Dark)

Normally, basic Markdown (`![alt](link)`) doesn't change images automatically based on the theme (light/dark mode).
But using **HTML inside Markdown,** you can!

You can use HTML `<picture>`, `<source>`, and `<img>` tags inside your Markdown file to switch images based on the user's system theme.

**Example (In HTML):**

```markdown
<picture>
  <source srcset="./assets/images/dark-mode.png" media="(prefers-color-scheme: dark)">
  <source srcset="./assets/images/light-mode.png" media="(prefers-color-scheme: light)">
  <img src="./assets/images/light-mode.png" alt="Image based on Theme">
</picture>
```

**Output:**

<picture>
  <source srcset="./assets/images/dark-mode.png" media="(prefers-color-scheme: dark)">
  <source srcset="./assets/images/light-mode.png" media="(prefers-color-scheme: light)">
  <img src="./assets/images/light-mode.png" alt="Image based on Theme">
</picture>

Explanation:

- If user's system is in dark mode, it will load dark-image.png.

- If user's system is in light mode, it will load light-image.png.

- Fallback img is also light-image.png.

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Embed YouTube Video

In Markdown, you can **embed a YouTube video** using a simple method with a link or by integrating **HTML** directly into your Markdown file. Here’s how you can do both:

**Example (Embed YouTube Video with an Image Link):**

```markdown
[![Video Title](https://img.youtube.com/vi/VIDEO_ID/maxresdefault.jpg)](https://www.youtube.com/watch?v=VIDEO_ID)
```

**Use to:**

- **Get YouTube Video_ID:** This is the string after `v=` in the YouTube URL. For example, in `https://www.youtube.com/watch?v=8SbUC-UaAxE`, the ID is `8SbUC-UaAxE`.

- Replace `VIDEO_ID` with the unique video ID from the YouTube URL.

- This will show an image (thumbnail) of the video and when clicked, the user will be redirected to the **YouTube page.**

**Example:**

```markdown
[![Guns N' Roses - November Rain](https://img.youtube.com/vi/8SbUC-UaAxE/maxresdefault.jpg)](https://www.youtube.com/watch?v=8SbUC-UaAxE)
```

**Output:**

[![Guns N' Roses - November Rain](https://img.youtube.com/vi/8SbUC-UaAxE/maxresdefault.jpg)](https://www.youtube.com/watch?v=8SbUC-UaAxE)

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Escaping Characters

**Escaping** means telling **Markdown to treat a character as plain text,** not as special formatting.  
Markdown uses special characters (like `*`, `_`, `#`,`[ ]`), so escaping is needed when you want them to appear literally.

### List of Characters You Can Escape

| Character | Description                    | Example (Without Escape)    |
| :-------- | :----------------------------- | :-------------------------- |
| `\`       | Backslash itself               | `\\Hello` → \Hello          |
| `` ` ``   | Backtick (code)                | `` `code` `` → `code`       |
| `*`       | Asterisk (bold/italic)         | `*bold*` → _bold_           |
| `_`       | Underscore (italic)            | `_italic_` → _italic_       |
| `{}`      | Curly braces                   | `{text}` → {text}           |
| `[]`      | Square brackets (links/images) | `[text]` → [text]           |
| `()`      | Parentheses (links/images)     | `(link)` → (link)           |
| `#`       | Hash (heading)                 | `# Heading` → # Heading     |
| `+`       | Plus (lists)                   | `+ Item` → + Item           |
| `-`       | Minus (lists)                  | `- Item` → - Item           |
| `.`       | Dot (lists)                    | `1. Item` → 1. Item         |
| `!`       | Exclamation mark (images)      | `![alt](url)` → ![alt](url) |
| `>`       | Greater than (quotes)          | `> Quote` → > Quote         |

### How to Escape Characters

Use a backslash `\` before the special character.

| You Write (With Escape) | You See                     |
| :---------------------- | :-------------------------- |
| `\*bold\*`              | bold (without formatting)   |
| `\_italic\_`            | italic (no formatting)      |
| `\# Heading`            | # Heading (not a header)    |
| `1\. Item one`          | 1. Item one (no auto list)  |
| `\![Image\](url)`       | (no image)                  |
| `\|Table\|`             | \|Table\| (no table format) |

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## HTML in Markdown

**Markdown fully supports raw HTML** — meaning you can directly embed HTML tags inside your .md files.

This is very useful when:

- Markdown Example is too limited

- You need more control (like tables, styled images, videos, divs)

**Some Common Use Cases:**

- **Complex tables** - Markdown tables are basic
- **Custom image attributes** - Add width, height, styles
- **Centering text/images** - Markdown can’t center easily
- **Videos/iframes** - Markdown doesn't support embeds
- **Div blocks** - Custom layout and styling

**Example - HTML inside Markdown:**

```html
<p align="center">his is a paragraph using HTML inside Markdown.</p>
```

**Output**

<p align="center">This is a paragraph using HTML inside Markdown.</p>

**GitHub README restrictions:**

- Disallows `<iframe>`, `<script>`, `<style>` for security reasons.

- Basic tags like `<p>`, `<img>`, `<table>`, `<div>`, `<span>` are allowed.

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## Footnotes

To add a footnote in Markdown, you use the following format:

- Add a superscript reference number inside square brackets ([1]) where you want the footnote to appear.

- Below the text, provide the reference using the same number in square brackets, followed by a colon and the footnote content.

**Example(Basic):**

```markdown
This is a sentence with a footnote reference.[^1]

[^1]: This is the footnote content.
```

**Output:**

This is a sentence with a footnote reference.[^1]

[^1]: This is the footnote content.

**Example(Footnote with Links):**

```markdown
Learn more about Markdown at [Markdown Guide](https://www.markdownguide.org).
```

You can also include links inside footnotes. This is useful for providing references or citing sources.

**Output:**

Learn more about Markdown at [Markdown Guide](https://www.markdownguide.org)[^2].

[^2]: The source of Markdown documentation is [here](https://www.markdownguide.org/).

<!-- START "Jump to Top"-->
<p align="right" style="font-size: 16px; font-weight: 600; margin-top: 24px;">
  <a href="#table-of-contents" style="text-decoration: none; color: #0366d6;">Jump to Top ▲</a>
</p>
<!-- END "Jump to Top" -->

## **📄 License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## **🤝 Contributing**

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
