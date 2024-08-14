---
# weight: 1
title : '标题'
description: "副标题."
tags: ["independence"]

aliases: ["{{ replace .File.ContentBaseName " " "-" | title }}"]
date : {{ .Date }}
author: "yanhua"
draft: false
canonicalURL: "https://canonical.url/to/page"

# cover:
#     image: "<image path/url>" # image path/url
#     alt: "<alt text>" # alt text
#     caption: "<text>" # display caption under cover
#     relative: false # when using page bundles set this to true
#     hidden: true # only hide on current single page
---