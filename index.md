---
layout: default.liquid
---
## Roxi's Public Diary

{% for post in collections.posts.pages %}
#### {{post.title}}

[{{ post.title }}]({{ post.permalink }})
{% endfor %}
