---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> ({{ post.date | date: '%d/%m/%Y' }})
    </li>
  {% endfor %}
</ul>

