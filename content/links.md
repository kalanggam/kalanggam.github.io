---
title: "Links"
date: 2022-12-13T19:49:03-06:00
draft: false
links:
  - title: GitHub
    description: GitHub is the world's largest software development platform.
    website: https://github.com
    image: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png
menu:
    main: 
        weight: 4
        params:
            icon: link
---

To use this feature, add `links` section to frontmatter.

This page's frontmatter:

```yaml
links:
  - title: GitHub
    description: GitHub is the world's largest software development platform.
    website: https://github.com
    image: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png
  - title: TypeScript
    description: TypeScript is a typed superset of JavaScript that compiles to plain JavaScript.
    website: https://www.typescriptlang.org
    image: ts-logo-128.jpg
```

`image` field accepts both local and external images.