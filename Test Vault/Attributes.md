---
title: Attributes Test
summary: |
  This test demonstrates how attributes are preserved in HTML output.
---

```pug
h2= fm.title
p(style="text-decoration: underline;")
  | #{fm.summary}
  | This paragraph is underlined because the #[code style] attribute is set to `"text-decoration: underline;"`.
```
