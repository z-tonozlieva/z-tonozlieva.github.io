---
title: Embracing the Jekyll Journey
author: Zori
date: 2023-08-15 20:55:00 +0800
categories: [Websites, Jekyll]
tags: [website,jekyll,blogging,github]
---

Enter Jekyll, a creation by Tom Preston-Werner, one of GitHub's co-founders. Jekyll welcomed me with open arms to the world of "Simple, blog-aware, static sites." No longer lost in a labyrinth of databases, I found myself in a single folder where my blog posts can live as Markdown files. Images resided in another folder, keeping everything neat and orderly.
The architecture offered a departure from the complex databases and dynamic rendering of WordPress, opting for static rendering that significantly reduced exposure to security vulnerabilities.

A pivotal advantage emerges in the seamless integration of Jekyll with GitHub Pages, facilitated by GitHub's acquisition of Jekyll's creator. Hosting the website on a repository named **username.github.io** enables GitHub Actions to orchestrate the compilation of content through Jekyll, generating the **_site** directory housing the fully rendered static website. This integration ensures both the preservation and accessibility of the blog content while reducing the potential for security breaches.

Creating new posts involves creating Markdown files under the **_posts** directory, each file containing post-specific metadata and content. A typical Markdown structure served as a template:

```markdown
---
title:  Embracing the Jekyll Journey
date:   2023-08-15 09:00:00
categories: [website, jekyll]
---

Enter Jekyll, a creation by Tom Preston-Werner
```

Check out [Jekyll](http://jekyllrb.com/) and get blogging in a sane way!

