---
layout: archive
title: "Awards"
permalink: /publications/
author_profile: true
---

* Bashford International Scholarship
* Corns Business Scholars
* Dean’s List
* International Economics Honor Society
* Christian Kamm Schollarship

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
