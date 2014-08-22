---
layout: post
title: Templating
---

    ---
    layout: post
    title: Templating
    ---
    
    {% raw %}{% include footer.html %}

    {% include footer.html param="value" %}
    
    {{ include.param }}
    
    {{ site.title }}
    
    {{ page.title }}
    
    {% gist parkr/931c1c8d465a04042403 %}{% endraw %}
    
[layout post](https://raw.githubusercontent.com/paven/regin/gh-pages/_layouts/post.html)
[layout default](https://raw.githubusercontent.com/paven/regin/gh-pages/_layouts/default.html)
[include sidebar](https://github.com/paven/jekyllTalk/blob/master/_includes/sidebar.html)
