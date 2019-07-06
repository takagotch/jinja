### jinja
---
https://github.com/pallets/jinja

```
{% extends 'base.html' %}
{% block title %}Memberlist{% endblock %}
{% block content %}
  <ul>
    {% for user in users %}
      <li><a href="{{ user.url }}">{{ user.username }}</a></li>
    {% endfor %}
  </ul>
{% endblock %}
```

```
<title></title>
<ul>
  {% for user in users %}
    <li><a href="{{ user.url }}">{{ user.username }}</a></li>
  {% endfor %}
</ul>
```

```
```


