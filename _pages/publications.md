---
layout: archive
title: "Ongoing Research"
permalink: /publications/
author_profile: true
---

## Peer-reviewed Publications

Title 1  
<details>
<summary>Abstract</summary>
  
</details>


## Working Papers

Title 2
<details>

<summary>Abstract</summary>
  
</details>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
