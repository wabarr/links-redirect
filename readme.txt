To add a new link redirect, add a file with the YAML header shown below to the redirects/ directory

The file should be named slug2redirectfrom.md

In the redirect_to: array, put a single entry containing the complete URL to redirect to (https://wabarr.com) in the example below. 

Once this file has been added and the site pushed to gitub you can visit go.wabarr.com/slug2redirectfrom and it will redirect to the redirect_to URL

---
permalink: /slug2redirectfrom
layout: page
redirect_to:
  - https://wabarr.com
---
