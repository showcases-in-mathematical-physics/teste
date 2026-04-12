---
layout: default
title: "Which are the Areas of Mathematical Physics?"
Author:
    - name: Alexandre Mendonça Rodrigues
      website: (sem link ainda)
      orcid: (dps coloca)
bibliography: 
    - (ver como colocar referências)
    - lima2010awakingvacuumrelativistic
---
<div class="page-meta">
  <p><strong>Autor:</strong> {{ page.author }}</p>
  
  {% if page.orcid %}
  <p>
    <strong>ORCID:</strong> 
    <a href="https://orcid.org/{{ page.orcid }}" target="_blank" rel="noopener">
      {{ page.orcid }}
    </a>
  </p>
  {% endif %}
  
  {% if page.university %}
  <p><strong>Afiliação:</strong> {{ page.university }}{% if page.department %} — {{ page.department }}{% endif %}</p>
  {% endif %}
  
  {% if page.email %}
  <p><strong>Email:</strong> <a href="mailto:{{ page.email }}">{{ page.email }}</a></p>
  {% endif %}
</div>
(Essa página é um teste)
