---
template: ContactPage
slug: contact
title: Contact Page
featuredImage: https://ucarecdn.com/e22a858a-b420-47af-99f6-ed54b6860333/
subtitle: This is the contact page subtitle.
address: 131 Toge Gose City Nara, JAPAN
phone: 0987 123 456
email: example@example.com
locations:
  - mapLink: ""
    lat: "34.4375296"
    lng: "135.7615772"
meta:
  description: This is a meta description.
  title: Contact Page
---

# Example contact form

This form is setup to use Netlify's form handling:

- the form action is set to the current absolute url: `action: '/contact/'`
- a name attribute is sent with the form's data `'form-name': 'Contact'`
- netlify data attributes are added to the form `data-netlify data-netlify-honeypot`

Find out more in the [Netlify Docs](https://www.netlify.com/docs/form-handling/).
