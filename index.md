---
---

# Who We Are

VIM (Visualization and Image Data Management) is an interdisciplinary academic association working together on visualization and image data management topics for bioemdical imaging and analysis. We aim to connect research labs, university hospitals, and open source partners. Its mission is to provide a platform for research and educational exchange and to join efforts in developing and standardizing data formats, platforms and interfaces for analyzing and communicating biomedical imaging data.

{% include section.html %}

## Highlights

{% capture text %}

VIM (Visualization and Image Data Management) is an interdisciplinary academic association working together on visualization and image data management topics for bioemdical imaging and analysis. We aim to connect research labs, university hospitals, and open source partners. Its mission is to provide a platform for research and educational exchange and to join efforts in developing and standardizing data formats, platforms and interfaces for analyzing and communicating biomedical imaging data.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
