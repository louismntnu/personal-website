---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: louis.o.martini@ntnu.no
      address:
        street: Alfred Getz' vei 1
        city: Trondheim
        postcode: '7034'
        country: Norway
        country_code: NO
      directions: Sentralbygg 2, 1256, Gløshaugen
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
