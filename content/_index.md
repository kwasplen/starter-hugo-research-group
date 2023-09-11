---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

# Leave hero block title empty
sections:
  - block: hero
    content:
      title:
      image:
        filename: cgcvenn.png
      text: |
        The **Chesapeake Global Collaboratory** (CGC) is an UMCES initiative to generate accelerated solutions to big problems
        by engaging diverse voices, novel approaches, and innovative tools.
        It will be a center of excellence for environmental research, teaching, and practice.

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        UMCES is conducting a series of meetings and events to advance the initiative with faculty and external partners.
    
        On August 3, a lunchtime webinar was held for all of UMCES to learn about the progress of the CGC and 
        to participate in its ongoing development.
        The webinar provided an overview of the CGC, followed by a presentation of specific research projects from UMCES faculty that 
        would fall within the collaboratory structure.
    
        The next milestone for the project will be the CGC Summit on September 28–29 at the Rita Rossi Colwell Center in Baltimore.
        It will feature plenary speakers Fred Tutman, ShaShi Shekhar, and Dr. Erica Key.
    design:
      columns: '1'
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
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
      view: card
      columns: '1'

- block: markdown
    content:
      title:
      subtitle:
      text: |
        ![screen reader text](logo.png "caption")
    design:
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: umcesfooter.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: actual
          text_color_light: true
      spacing:
        padding: ['4px', '0', '4px', '0']
      # css_class: fullscreen

  # figure out cta issue later, if wanted
  # - block: markdown
    # content:
      # title:
      # subtitle:
      # text: |
        # {{< cta cta_link="./people/" cta_text="Meet the Team →" >}}
        # {{% cta link="./people/" text="Meet the Team →" %}}
    # design:
      # columns: '1'
---
