---
layout: default
---

# {{ page.title }}

{{ content }}

{% for paste in site.pastes %}
## {{ paste.title }}

{{ paste.content }}

*Posted on {{ paste.date | date: "%B %d, %Y" }}*

---
{% endfor %}
