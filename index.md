---
title: "Jessica N. Howard"
layout: splash
permalink: /splash-page/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/splash/test_splash.jpeg
  actions:
    - label: "About Me"
      url: "#test-link"
excerpt: "Website is currently under construction. Check back later."
feature_row:
  - image_path: /assets/splash/placeholder.jpeg
    title: "Placeholder 1"
    excerpt: "Sample text 1 with **markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/splash/placeholder.jpeg
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/splash/placeholder.jpeg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row_left:
  - image_path: /assets/splash/test_splash.jpeg
    title: "Left aligned placeholder 1"
    excerpt: "Left-aligned image centered with"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---
{% include feature_row %}
{% include feature_row id="feature_row_left" type="left" %}
