---
title: Home
slug: /
sections:
  - type: GenericSection
    subtitle: ''
    text: ''
    actions:
      - type: Button
        label: Get started
        altText: ''
        url: google.com
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    badge:
      type: Badge
      label: This is a badge
      color: text-primary
    colors: bg-dark-fg-light
    styles:
      self:
        alignItems: center
        padding:
          - pt-0
        flexDirection: ''
    media:
      type: VideoBlock
      title: Title of the video
      url: 'https://www.youtube.com/watch?v=RvGaSPTcTxc'
      autoplay: true
      loop: true
      muted: false
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    backgroundImage:
      type: BackgroundImage
      altText: ''
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
      url: /images/background.webp
  - type: GenericSection
    title:
      type: TitleBlock
      text: Business Consulting
      color: text-dark
    subtitle: Be in good company
    text: >
      A service that provides advice and guidance to startups and small
      businesses.
    actions:
      - type: Button
        label: Get started
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
      - type: Link
        label: See Tutorials
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
    badge:
      type: Badge
      label: This is a badge
      color: text-primary
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
    media:
      type: VideoBlock
      title: Title of the video
      url: /images/ro_promo_video.mp4
      autoplay: true
      loop: true
      muted: true
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: auto
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
