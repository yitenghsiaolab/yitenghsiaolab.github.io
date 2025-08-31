---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: Nano-Optics & Biophysics Lab
        content: 'Hsiao Lab @ NYCU Electrophysics'
        align: center
        background:
          image:
            filename: Banner.png
            filters:
              brightness: 0.7
          position: right
          color: '#666'

      - title: Nano-Optics & Biophysics Lab
        content: 'Hsiao Lab @ NYCU Electrophysics'
        align: center
        background:
          image:
            filename: Lab_5.png
            filters:
              brightness: 0.7
          position: right
          color: '#666'
          
      - title: Nano-Optics & Biophysics Lab
        content: ''
        align: right
        background:
          image:
            filename: Lab_3.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../Lab_website/contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000

#  - block: markdown
#    content:
#      title:
#      subtitle: ''
#      text:
#    design:
#      columns: '1'
#      background:
#        image: 
#          filename: Banner.png
#          filters:
#            brightness: 1
#          parallax: false
#          position: center
#          size: cover
#          text_color_light: true
#      spacing:
#        padding: ['20px', '0', '20px', '0']
#      css_class: fullscreen
  
  - block: hero
    content:
      title: |
        Welcome to 
      image:
        filename: Lab_1.png
      text: |
        Hsiao Lab @ NYCU Electrophysics
        <br><font size="5">
        We are developing innovative optical microscope techniques. 
        </font>

  - block: collection
    content:
      title: News
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: stream #card
      columns: '2' 

  - block: collection
    content:
      title: Research
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: research
    design:
      view: card #stream
      columns: '2' 

  - block: collection
    content:
      title: Latest Publication
      text: ""
      count: 1
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '2'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="../Lab_website/contact/" cta_text="Join us →" %}}
    design:
      columns: '1'
---
