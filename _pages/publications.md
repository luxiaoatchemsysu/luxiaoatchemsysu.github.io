---
title: "Publications"
layout: gridlay
excerpt: "Publications."
sitemap: false
permalink: /publications/
---


<p></p>

(<b>*</b> Corresponding author; Group members are shown in bold )

<p></p>

{% for publi in site.data.publist %}

{{ publi.authors }}: {{ publi.title }}, <b><em>{{  publi.journal }}</em></b>, {{ publi.year }}. <a href="{{ publi.url }}">{{ publi.display }}</a>
<br /> 

{% endfor %}
