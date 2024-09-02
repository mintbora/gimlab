---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
background: images/backgrounds/anschutz.jpg
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is part of the [College of Natural Science and Public Health and Safety in Chosun University](https://eng.chosun.ac.kr/eng/1882/subview.do)'s [Department of Biomedical Science](https://biomed.chosun.ac.kr/biomed/index.do) and [the Research Center of Gwangju Alzheimer's and Related Dementia(GARD) cohort](https://dss.niagads.org/cohorts/gwangju-alzheimers-and-related-dementia-gard/).
We are a team located on the 3rd floor of the [Genetic Engineering Building].(https://www3.chosun.ac.kr/sites/eng/files/Campus_map_English.pdf).

{%
  include figure.html
  image="images/contact/health-ai-logo.png"
  link="https://medschool.cuanschutz.edu/"
  width="400px"
%}

{%
  include button.html
  type="email"
  text=site.links.email
  link=site.links.email
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Anschutz+Health+Sciences+Building/@39.7454721,-104.8418929,15z/data=!4m2!3m1!1s0x0:0x85f675e778fce18c?sa=X&ved=2ahUKEwjd_MfInpL6AhWEhIkEHd6WDIcQ_BJ6BAhkEAU"
%}

{% capture content %}
{% include figure.html image="images/contact/AHSB.jpg" %}
{% include figure.html image="images/contact/cu-aerial.jpg" %}
{% include figure.html image="images/contact/cu-photo.jpg" %}
{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}
