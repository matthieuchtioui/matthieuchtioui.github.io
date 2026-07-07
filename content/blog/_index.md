---
title: Blog
summary: My blog posts
type: landing

cascade:
  - target:
      path: '{/blog/*/**}'
    type: docs
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: blog
    content:
      title: Blog
      filters:
        tag: Blog
        kinds:
          - section
    design:
      view: article-grid
      show_read_time: true
      show_date: false
      show_read_more: false
      columns: 1
---
