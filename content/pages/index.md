---
type: PageLayout
title: IA Lab Studio | Home principal
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: 'IA Lab Studio: Laboratorio de Automatización y Presencia Digital'
    subtitle: >-
      Diseñamos y automatizamos ecosistemas digitales para negocios reales. 
      Desde Granada ayudamos a marcas y profesionales a escalar con presencia
      digital, branding y automatización inteligente.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        flexDirection: row-reverse
        textAlign: left
    type: HeroSection
    actions:
      - type: Button
        label: Ver proyectos
        altText: ''
        url: /
        showIcon: true
        icon: chevronRight
        iconPosition: right
        style: primary
        elementId: ''
    text: |
      Conecta tu negocio con la nueva era digital.
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: Ver todos los proyectos
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
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
    subtitle: Casos reales de automatización y presencia digital
    title: Proyectos y sistemas creados por IA Lab Studio
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: 'Ideas, guías y automatización aplicada'
    showFeaturedImage: false
    actions:
      - type: Link
        label: Ver todas las publicaciones
        url: /blog
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        textAlign: left
    title: Publicaciones y recursos
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project? Tell me more...\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        self:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
socialImage: /images/Logo Violeta B.png
metaTitle: 'IA Lab Studio: Laboratorio de Automatización y Presencia Digital en Granada'
metaDescription: >-
  Diseñamos, conectamos y automatizamos ecosistemas digitales. Desde Granada
  ayudamos a marcas, agencias y profesionales a crear una presencia digital
  inteligente y modular.
metaTags:
  - type: MetaTag
    property: 'og:title'
    content: >-
      IA Lab Studio: Laboratorio de Automatización y Presencia Digital en
      Granada
  - type: MetaTag
    property: 'og:description'
    content: >-
      Diseñamos, conectamos y automatizamos ecosistemas digitales desde Granada.
      Presencia digital inteligente y modular para negocios reales.
  - type: MetaTag
    property: 'og:url'
    content: 'https://www.ialabstudio.com/'
  - type: MetaTag
    property: 'og:type'
    content: website
  - type: MetaTag
    property: 'og:image'
    content: >-
      https://devserver-preview--ialabstudio.netlify.app/_static/app-assets/public/images/Logo%20Violeta%20B.png
---
