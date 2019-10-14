+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10 # Order that this section will appear.

# Slide interval. 
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "400px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.

[[item]]
  title = "Check out our ongoing projects"
  content = ""
  align = "center"

  overlay_color = "#56B4E9"  # An HTML color value.
  overlay_img = "headers/desk.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.2  # Darken the image. Value in range 0-1.
  
  cta_label = "See ongoing projects"
  cta_url = "/projects"
  cta_icon_pack = "fas"
  cta_icon = "tasks"
  
  use_pages = false

[[item]]
  title = "Join us!"
  content = "Interested in joining our lab? Get in touch!"
  align = "center"

  overlay_color = "#56B4E9"  # An HTML color value.
  overlay_img = "headers/idea.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.2  # Darken the image. Value in range 0-1.
  
  cta_label = "Join us"
  cta_url = "/contact"
  cta_icon_pack = "fas"
  cta_icon = "file-signature"
  
  use_pages = false
  
[[item]]
  title = ""
  content = ""
  align = "center"

  use_pages = true
  pages_title = "Recent and upcoming talks"
  pages_type = "talk"

  overlay_color = "#56B4E9"  # An HTML color value.
  overlay_img = "headers/present.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.2  # Darken the image. Value in range 0-1.
+++
