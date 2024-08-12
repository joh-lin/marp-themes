---
marp: true

title: 'Marp Showcase'
author: 'joh-lin'
description: 'Slides to showcase features of Marp and the look of my themes'

theme: dlr
paginate: true
transition: iris-in 0.2s
footer: 'Find this theme at https://github.com/joh-lin/marp-themes'
---


<!-- 
_class: title
_paginate: skip
_footer: ''
-->

# Marp Showcase more content that displays in a new line
## and my themes, that are based on the ouranos theme, which is in turn base on default
</br></br>
by Johannes

---
## The frontmatter
```yaml
---
marp: true

title: 'Marp Showcase'
author: 'joh-lin'
description: 'Slides to showcase features of Marp and the look of my themes'

theme: ouranos
paginate: true
transition: iris-in 0.2s
footer: 'https://github.com/joh-lin'
---
```
---
## More directives
<!-- _backgroundImage: url('https://plus.unsplash.com/premium_photo-1701520913496-503a71946555?w=900&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8cHJlc2VudGF0aW9uJTIwYmFja2dyb3VuZHxlbnwwfHwwfHx8MA%3D%3D') -->


<div class="columns"><div class="col">

- backgroundColor
- backgroundImage
- backgroundPosition
- backgroundRepeat
- backgroundSize
</div><div class="col">

- color
- size
- style
- header 
- class
</div></div>

---
## Image formatting is the practice of modifying an image until it looks like you want it to look
- This is just some placeholder
    - content because i have not
    - written anything for 
        - image formatting yet 
- but require some content and also some longer lines to test how the template, but require some content and also some longer lines to test how the template
    - will work out in the end 
- lorem ipsum dolor sit amet, consetetur sadipscing elitr

Also i need some normal text in here too.

---
## Background formatting
1. The same for background formatting, except that i
2. Am now using
    1. An ordered list instead.

---
<!-- _class: chapter -->
# Theme Showcase

---
## Columns
This produces a slide with two columns.
```markdown
## Heading
<div class="columns"><div class="col">

- its important
- to always leave
</div><div class="col">

- an empty line
- below html elements
</div></div>
```

---
## The title page
The `</br>` tags are used to move the author text down a little.
```markdown
<!-- 
_class: title
_paginate: skip
_footer: ''
-->
# Marp Showcase
## (and my themes)
</br></br>
by Johannes
```
`_class: title` is important. The other directives hide pagination and footer.

---
## The chapter page
The chapter page works the same as the title page, except for using the class `chapter`.

---
## Inspiration for this Theme:
https://veritablehokum.com/comic/the-greek-god-family-tree/
![bg right](https://veritablehokum.com/wp-content/uploads/2015/04/Greek-God-Family-Tree2.jpg)

---