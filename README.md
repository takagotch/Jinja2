### Jinja2
---
https://palletsprojects.com/p/jinja/

https://github.com/pallets/jinja

```
{% extends "layout.html" %}
{% block body %}
  <ul>
  {% for user in users %}
    <li><a href="{{ user.url }}">{{ user.username }}</a></li>
  {% endfor %}
  </ul>
{% endblock %}

```

```sh
pip install -U Jinja2
```

```
```


