---
type: PageLayout
title: Contatti
sections:
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Contatti
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: >-
      Siamo sempre pronti ad ascoltarti! Se hai domande, richieste o vuoi sapere
      di più sui nostri servizi, non esitare a metterti in contatto con noi. Ti
      risponderemo il prima possibile!
    items:
      - type: FeaturedItem
        title: ✉️ lp@lorenzoperucci.com
        subtitle: ''
        text: ''
        actions:
          - type: Link
            label: Send email
            altText: Play
            url: 'mailto:lp@lorenzoperucci.com'
            showIcon: true
            icon: mail
            iconPosition: right
            style: secondary
            elementId: ''
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
        tagline: e-mail
      - type: FeaturedItem
        title: Open Source Engineer
        subtitle: Marketing
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: Senior Software Engineer
        subtitle: Engineering
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
    actions:
      - type: Button
        label: Apply now
        url: /
        icon: arrowRight
        iconPosition: right
        style: primary
    variant: toggle-list
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pb-40
          - pt-16
          - pl-3
          - pr-3
        justifyContent: center
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: Scrivici qui!
      color: text-dark
    subtitle: >-
      Se preferisci, puoi anche compilare il modulo sottostante e ti
      risponderemo al più presto!
    text: ''
    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Nome e Cognome
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Il tuo messaggio
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Invia
        icon: arrowRight
        iconPosition: right
        style: primary
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    badge:
      type: Badge
      label: ''
      color: text-primary
    colors: bg-light-fg-dark
slug: contatti
isDraft: false
seo:
  type: Seo
  metaTitle: Contatti - LP PRODUCTIONS
  metaDescription: Write here your new page's description including most relevant keywords.
  addTitleSuffix: true
  socialImage: /images/main-hero.jpg
  metaTags: []
---
