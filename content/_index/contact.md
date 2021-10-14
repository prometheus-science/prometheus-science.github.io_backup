+++
fragment = "contact"
#disabled = true
date = "2021-09-10"
weight = 1100
#background = "light"
form_name = "defaultContact"

title = "Get in touch"
subtitle  = "Looking forward to share knowledge and expertise to make research and education more accessible!"

# PostURL can be used with backends such as mailout from caddy
post_url = "https://formspree.io/f/mknpbwnr" #default: formspree.io  
email = "andre@prometheus-science.com"
button = "Send message" # defaults to theme default
#netlify = false

# Optional google captcha
[recaptcha]
  sitekey = "6LcM8wYbAAAAAPQU9tPqWgdwugRdK6mCwK0QWYZv"

[message]
  #success = "" # defaults to theme default
  #error = "" # defaults to theme default

# Only defined fields are shown in contact form
[fields.name]
  text = "Your Name *"
  #error = "" # defaults to theme default

[fields.email]
  text = "Your Email *"
  #error = "" # defaults to theme default

#[fields.phone]
#  text = "Your Phone *"
#  #error = "" # defaults to theme default

[fields.message]
  text = "Your Message *"
  #error = "" # defaults to theme default

# Optional hidden form fields
# Fields "page" and "site" will be autofilled
[[fields.hidden]]
  name = "page"

[[fields.hidden]]
  name = "someID"
  value = "example.com"
+++
