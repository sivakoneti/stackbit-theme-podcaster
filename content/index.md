---
title: Home
sections:
  - type: hero_section
    title: Welcome to DIYJam Podcast
    content: >-
      A podcast for Web developers interested in building Jamstack websites. Hosted by Jhon Doe
    actions:
      - label: Subscribe to Podcast
        url: /thank-you
        style: primary
    image: images/hero.png
    image_alt: Hero section placeholder image
    media_position: left
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/bc-2.jpg
    background_image_repeat: no-repeat
    background_image_size: cover
    background_image_opacity: 20
    has_border: true
  - type: blog_feed_section
    title: Latest Episodes
    blog_feed_cols: three
    enable_cards: true
    show_recent: true
    recent_count: 10
    show_image: true
    show_date: true
    show_categories: false
    show_author: false
    show_excerpt: false
    align: center
    padding_top: medium
    padding_bottom: medium
    has_border: true
    background_color: none
    background_image: images/webb.svg
    background_image_repeat: repeat
    background_image_size: auto
    background_image_opacity: 100
  - type: grid_section
    title: Subscribe
    grid_items:
      - title: Apple Podcasts
        title_align: center
        content_align: center
        actions:
          - label: Subscribe
            url: /thank-you
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        actions_align: center
        image: images/icon-1.svg
        image_alt: Partnering and sponsorships icon
        image_position: top
        image_align: center
        image_has_padding: true
      - title: Spotify
        title_align: center
        content_align: center
        actions:
          - label: Subscribe
            url: /thank-you
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        actions_align: center
        image: images/icon-2.svg
        image_alt: Help and support icon
        image_position: top
        image_align: center
        image_has_padding: true
      - title: Overcast
        title_align: center
        content_align: center
        actions:
          - label: Subscribe
            url: /thank-you
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        actions_align: center
        image: images/icon-3.svg
        image_alt: Other queries icon
        image_position: top
        image_align: center
        image_has_padding: true
    grid_cols: three
    grid_gap_horiz: medium
    grid_gap_vert: medium
    enable_cards: false
    align: center
    padding_top: large
    padding_bottom: large
    background_color: secondary
    background_image: images/bc.jpg
    background_image_repeat: no-repeat
    background_image_size: cover
    background_image_opacity: 10
  - type: grid_section
    title: Partners
    subtitle: 2021 Supporters
    align: center
    grid_items:
      - image: images/logo-1.svg
        image_alt: Contentful logo
        image_align: center
      - image: images/logo-2.svg
        image_alt: Netlify logo
        image_align: center
      - image: images/logo-3.svg
        image_alt: Gatsby logo
        image_align: center
      - image: images/logo-4.svg
        image_alt: Sanity logo
        image_align: center
      - image: images/logo-5.svg
        image_alt: Contentful logo
        image_align: center
      - image: images/logo-6.svg
        image_alt: Netlify logo
        image_align: center
      - image: images/logo-7.svg
        image_alt: Gatsby logo
        image_align: center
      - image: images/logo-8.svg
        image_alt: Sanity logo
        image_align: center
    grid_cols: four
    grid_gap_horiz: medium
    grid_gap_vert: medium
    has_border: true
  - type: form_section
    content: |-
      ## Ask A Question
      I'm OK with any kind of questions and will answer as many as I possibly can.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: textarea
        name: message
        label: Question
        default_value: Your question
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Submit
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: none
    background_image: images/webb.svg
    background_image_repeat: repeat
    background_image_size: auto
    background_image_opacity: 100
layout: advanced
---
