---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

{% for post in site.posts %}
<a href="{{ post.url }}">{{post.title}} - {{ post.date | date_to_string }}</a>
{% endfor %}
