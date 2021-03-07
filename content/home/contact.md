---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle: Use this contact form to reach out with requests to collaborate, conference or speaking engagement opportunities, or ideas for future post content. If you need help with an R, Python, or SQL script, or you just can't get an Excel formula to work right, please seek help from an online community such as [Stack Overflow](https://stackoverflow.com/).

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: formspree
    formspree:
      id: myybqrzp
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false
  
design:
  columns: '2'
---
