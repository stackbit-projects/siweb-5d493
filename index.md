---
title: Home
hide_title: true
sections:
  - type: section_hero
    template: section_hero
    title: 'Hi, I''m Si'
    section_id: hero
    content: >
      I have been building websites for over twenty years.  My goal as a web
      developer, publication designer and IT consultant is to help clients
      achieve success in their chosen field, whatever that happens to be.  My
      approach is to start with where clients are already at and work with what
      tools they feel most comfortable using.  Not to impose "my way" of doing
      things, though I am happy to suggest better or easier alternatives if that
      is desired. I have worked with hundreds of frameworks and software
      projects and always ready to lean new ones.  Adaptability is key!
  - type: section_content
    template: section_content
    title: About
    section_id: about
    content: >-
      This is the "about" excerpt. It can be used to provide a paragraph about
      yourself that people can read on the homepage to get a sense of who you
      are. There also exists a dedicated about page where you can write more
      about yourself for those who are interested.
    actions:
      - type: action
        template: action
        label: Contact Me
        url: /contact
        style: button
  - type: section_posts
    template: section_posts
    title: Recent Posts
    section_id: recent-posts
    posts_number: 4
    actions:
      - type: action
        template: action
        label: View Blog
        url: blog/index.html
        style: button
seo:
  type: stackbit_page_meta
  template: stackbit_page_meta
  title: Stackbit Fresh Theme
  description: The preview of the Fresh theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Fresh Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Fresh theme
      keyName: property
    - name: 'og:image'
      value: images/4.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Fresh Theme
    - name: 'twitter:description'
      value: The preview of the Fresh theme
    - name: 'twitter:image'
      value: images/4.jpg
      relativeUrl: true
layout: advanced
---
