---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: Joaquin.Alcaniz@uab.cat
  address:
    street: Mòdul de Recerca A, Parc de Recerca de la UAB
    city: Bellaterra
    region: Barcelona
    postcode: '08193'
    country: España
    country_code: ES
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/jacolomer2'

design:
  columns: '2'
---
