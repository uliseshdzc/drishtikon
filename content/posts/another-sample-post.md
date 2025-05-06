---
date: '2025-03-20T10:20:53-04:00'
draft: false
tags: ['LaTeX','Typesetting', Photos]
title: 'Another Sample Post'
math: true 
---

## Typsetting

We use [KaTeX](https://katex.org/)  for mathematics typesetting. Here is an in-line example : \(G/\text{ker } \phi \cong \text{im } \phi\).

$$|G| = |Z(G)| + \sum_{i}[G:C_{G}(x_{i})]$$

Want to reference things? Here is a footnote. [^1]

## Other Content and Styles 

Using Markdown, we can add tables: 

| A | B |
|:----:|:----:|
| a1 | b1 |
| a2 | b2 |
| a3 | b3 |

Here is some `inline code`. Here is the same {{< inlinecode "python" >}}inline code{{< /inlinecode >}} but with syntax highlighting. Here is an example of inline, syntax highlighted code in Java: {{< inlinecode "java" >}} String foo = Integer.toString(x); {{< /inlinecode >}}

You can even use blockquotes. 

> Today is not yesterday, and will never be tomorrow. 

[^1]: Your great reference. 