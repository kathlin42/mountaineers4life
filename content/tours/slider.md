---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: High Altitude Alpine Tours
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: highaltitude.jpg
      link:
        icon: mountain
        icon_pack: fas
        text: Explore Tours
        url: highaltitude/

    - title: Via Ferrata
      align: center
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: viaferrata.jpg
      link:
        icon: mountain
        icon_pack: fas
        text: Explore Tours
        url: viaferrata/

    - title: Mountain Traversing
      align: center
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
      link:
        icon: mountain
        icon_pack: fas
        text: Explore Tours
        url: traversing/

---
