---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Carolina Media & Protest Research Group
      image:
        filename: 6ffeadec0f46574fe83a759a8b7094367ddf2d74803b3206df499512.png
      text: |
        <br>
        
        The **Carolina Media & Protest Research Group (CMAP)** is a collection of faculty, graduate students and undergraduates affiliated with the [University of North Carolina, Chapel Hill Sociology Department](https://sociology.unc.edu) studying collective action and the media. 
  
  - block: collection
    id: section-1
    content:
      title: Recent Publications
      #text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
      # Display content from the `content/post/` folder
      filters:
        folders:
          - publication
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose your content listing view - here we use the `showcase` view
      view: compact
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true
  - block: collection
    id: section-2
    content:
      title: Recent Presentations
      #text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
      # Display content from the `content/post/` folder
      filters:
        folders:
          - presentation
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose your content listing view - here we use the `showcase` view
      view: compact
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true
  #- block: collection
  #  content:
  #    title: Latest News
  #    subtitle:
  #    text:
  #    count: 5
  #    filters:
  #      author: ''
  #      category: ''
  #      exclude_featured: false
 #       publication_type: ''
#        tag: ''
#      offset: 0
#      order: desc
#      page_type: post
#    design:
#      view: card
#      columns: '1'
#  
#  - block: markdown
#    content:
#      title:
#      subtitle: ''
#      text:
#    design:
#      columns: '1'
#      background:
#        image: 
#          filters:
#            brightness: 1
#          parallax: false
#          position: center
#          size: cover
#          text_color_light: true
#      spacing:
#        padding: ['20px', '0', '20px', '0']
#      css_class: fullscreen
---