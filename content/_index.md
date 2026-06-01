---
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      background:
        gradient_mesh:
          enable: true
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: 'My Research'
      subtitle: ''
      text: 'Welcome to my academic portfolio.'
    design:
      columns: '1'
  - block: collection
    id: news
    content:
      title: Recent News
      page_type: blog
      count: 5
      order: desc
    design:
      view: card
---
