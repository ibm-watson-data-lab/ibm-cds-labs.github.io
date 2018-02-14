---
layout: layout-about
title: About
id: about
permalink: about
---

<section class="section-block about-section">
  <h3>About</h3>
  <p>
    We are a team of developer advocates who work to make data simple and accessible on the IBM Watson Data Platform.
  </p>
</section>
<section id="team-list" class="section-block">
  <h3>Team</h3>
  {% include team-list.html %}
</section>
<section id="get-involved" class="section-block">
  <h3>Get Involved</h3>
  {% capture contributor %}{% include contributor.md %}{% endcapture %}
  {{ contributor | markdownify }}
</section>