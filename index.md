---
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /images/header/header_p17kagk.jpg
  cta_label: "Download"
  cta_label: "Διαβάστε ένα δωρεάν απόσπασμα"
  cta_url: "https://leanpub.com/pibook"
  
excerpt: 'Σχεδιασμός και κατασκευή συνεργατικών συστήματων για ένα οικοσύστημα χρηστών, συσκευών, και υπηρεσιών.'
---

<div class="feature__wrapper">

  {% assign random = site.time | date: "%s%N" | modulo: site.biography.size %}

  {% include feature_col.html id="biography" type="left" index=random %}

  {% assign random = site.time | date: "%s%N" | modulo: site.gallery.size %}

  {% include feature_col.html id="gallery" type="center" index=random %}

  {% assign random = site.time | date: "%s%N" | modulo: site.case-study.size %}

  {% include feature_col.html id="case-study" type="right" index=arduino.md %}

<div>
