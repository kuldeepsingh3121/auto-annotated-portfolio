---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - type: MediaGallerySection
    title: ''
    subtitle: ''
    images:
      - type: ImageBlock
        url: /images/gallery-1.jpg
        altText: Image one
        caption: Image one caption
        elementId: ''
      - type: ImageBlock
        url: /images/gallery-2.jpg
        altText: Image two
        caption: Image two caption
        elementId: ''
      - type: ImageBlock
        url: /images/gallery-3.jpg
        altText: Image three
        caption: Image three caption
        elementId: ''
      - type: ImageBlock
        url: /images/gallery-4.jpg
        altText: Image four
        caption: Image four caption
        elementId: ''
    colors: colors-f
    spacing: 16
    columns: 4
    aspectRatio: '4:3'
    showCaption: false
    enableHover: true
    elementId: ''
    styles:
      self:
        height: auto
        width: full
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        textAlign: center
  - type: HeroSection
    title: Web Developer
    subtitle: >-
      I'm Kuldeep singh aspiring Full-Stack Web Development with a passion for
      creating responsive and user- friendly web applications. Currently
      pursuing B.Tech in AIML , I have a strong foundation in HTML, CSS,
      JavaScript , and I am actively learning DSA in Java . Eager to gain
      hands-on experience, collaborate on real-world projects, and grow in the
      tech industry.
    actions:
      - type: Button
        label: Resume
        altText: ''
        url: 'file:///C:/Users/Kuldeep%20Singh/Downloads/My%20Resume.pdf'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    media:
      type: ImageBlock
      url: /images/photo1.jpg
      altText: Hero image
      caption: Caption of the image
      elementId: ''
    colors: colors-a
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        flexDirection: row
        textAlign: left
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions: []
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-a
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        textAlign: left
    subtitle: Projects
  - type: LabelsSection
    title: Skills
    subtitle: ''
    items:
      - type: Label
        label: HTML
        url: ''
      - type: Label
        label: CSS
        url: ''
      - type: Label
        label: JavaScript
        url: ''
      - type: Label
        label: Bootstrap
        url: ''
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        textAlign: left
  - type: FeaturedProjectsSection
    subtitle: ''
    actions:
      - type: Link
        label: ''
        altText: ''
        url: ''
        showIcon: false
        icon: arrowRight
        iconPosition: right
        elementId: ''
    projects:
      - content/pages/projects/React-JS-Masterclass.md
      - content/pages/projects/Placement-Preparation.md
    colors: colors-f
    variant: variant-a
    elementId: ''
    showDate: false
    showDescription: false
    showFeaturedImage: true
    showReadMoreLink: false
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        textAlign: left
    title: Certificates
  - type: ContactSection
    title: Contact Me
    text: I'm look forward to hearing from you.
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: false
          placeholder: Your name
          width: 1/2
          isRequired: 'true'
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: false
          placeholder: Your email
          width: 1/2
          isRequired: 'true'
        - type: TextareaFormControl
          name: message
          label: Tell me about your project
          hideLabel: true
          placeholder: Tell me about your project
          width: full
          isRequired: true
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
          isRequired: 'false'
      submitLabel: Send Message
      elementId: contact-form
      styles:
        self:
          textAlign: left
    media:
      type: ImageBlock
      url: /images/contact.jpg
      altText: Contact form image
      caption: Caption of the image
      elementId: ''
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        flexDirection: row
        textAlign: left
socialImage: /images/photo1.jpg
---
