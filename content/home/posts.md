---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 13

title: Recent Studies
subtitle:

content:
  # Filter on criteria
  filters:
    folders:
      - post
    tag: ''
    publication_type: ''
    author: ''
    exclude_featured: false
    exclude_future: false
    exclude_past: false
  # Choose how many pages you would like to display (0 = all pages)
  count: 3
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc

design:
  # Choose a view for the listings:
  view: compact
  columns: '2'
  background:
    image: posts.jpg
    image_darken: 0.7
    image_parallax: true
    image_position: right
    image_size: cover
    text_color_light: true
  spacing:
    padding: ["20px", "0", "20px", "0"]
---
