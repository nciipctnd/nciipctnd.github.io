---
title: 'Home'
date: 2025-08-15
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Landing Page
      text: This is the landing page of the website
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: ""
      background:
        color: ""
        image:
          # Add your image background to `assets/media/`.
          filename: ""
          filters:
            brightness: 0.5
  - block: features
    id: features
    content:
      title: What is available on the website
      text: Use the menu items to do the following
      items:
        - name: Documentation
          description: Access the technical documentation.
        - name: Blog
          description: Access the updates.
        - name: Resources
          description: Access the links to downloadable resources. 
        - name: Community
          description: Engage with the community.
---
