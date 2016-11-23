---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: rails_tutorial
---

{% for chapter in site.chapters %}
  <div class="chapter">
    <a href="{{chapter.url}}">
      {{ chapter.number }} {{ chapter.title }}
    </a>
  </div>
{% endfor %}