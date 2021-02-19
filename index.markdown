---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
Got a JUG not listed here?
It's easy to add.  

{% for jug in site.jugs %}
  <h2>
    <a href="{{ jug.url }}">
      {{jug.location}} - {{jug.name }}
    </a>

  </h2>
{% endfor %}
