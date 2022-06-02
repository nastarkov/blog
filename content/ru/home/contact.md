---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Контакты
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
  email: test@example.org
  phone: 888 888 88 88
  address:
    street: Чкалова 50
    city: Москва
    region: 
    postcode: '94305'
    country: Россия
    country_code: RU
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  

design:
  columns: '2'
---
