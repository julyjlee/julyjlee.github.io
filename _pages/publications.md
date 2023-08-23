---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% if !site.publications %}
  I'm working on it right now! Wait for a second please.
{% endif %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
