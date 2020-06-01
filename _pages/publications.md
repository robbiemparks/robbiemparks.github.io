---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<iframe width="100%" height="1000" src="https://scholar.google.ch/citations?user=5aU5eEAAAAAJ&hl=en"></iframe>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
