---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="https://scholar.google.com/citations?hl=en&user=7daNLEAAAAAJ&view_op=list_works&gmla=AKKJWFe5gcSsqvqmLdHVrzeP5B2RM2TYtf3XT778Q4p2qYxqyWfy67jA_tm7A8NYMucAdj_qfuQrL00DLxHK-rmB" target="_blank">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
