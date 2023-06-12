---
title: Team
nav:
  order: 2
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: current" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: current" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: current" %}
{% include list.html data="members" component="portrait" filters="role: staff, group: current" %}

{% include section.html background="images/background.jpg" dark=true %}

# Alumni

{% include section.html %}

{% include list.html data="members" component="portrait" filters="group: alumni" %}