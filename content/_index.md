---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 中国科学院自动化研究所
        content: 紫东太初大模型研究中心——视频与图像分析组
        align: right
        background:
          image:
            filename: casia.jpeg
            filters:
              brightness: 0.7
          position: center
          color: '#666'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ./contact/


      - title: 代表性工作_1
        content: 名称，简介
        align: left
        background:
          image:
            filename: blank.png
            filters:
              brightness: 0.7
          position: butto
          color: '#666'
        link:
          icon: book
          icon_pack: fas
          text: Read paper
          url: www.arxiv.org


      - title: 代表性工作_2
        content: 名称，简介
        align: left
        background:
          image:
            filename: blank.png
            filters:
              brightness: 0.7
          position: butto
          color: '#666'
        link:
          icon: book
          icon_pack: fas
          text: Read paper
          url: www.arxiv.org

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 2000
---
