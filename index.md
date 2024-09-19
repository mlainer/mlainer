---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
title: "Welcome to My Scientific Page"
header:
  overlay_image: /assets/images/header-bg.jpg # Optional background image
  overlay_filter: 0.5 # Adjust the opacity of the image
  caption: "Photo Credit: [Martin Lainer]"
  actions:
    - label: "View Research"
      url: "/research"
      class: "btn btn-primary"
excerpt: "Currently I am a scientific collaborator at MeteoSwiss, specializing in radar meteorology."

intro:
  - excerpt: "I am currently researching [Key Research Topics] and collaborating with [Partners/Institutions]."

<div class="intro">
  {{ page.intro[0].excerpt }}
</div>

{% include feature_row %}

## Quick Links
- [Research](research)
- [Publications](publications)
- [CV](cv)