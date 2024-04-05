---
title: "{{ replace .Name "-" " " | title }}"
# date: {{ .Date }}
date: "{{ dateFormat "2006-01-02" .Date }}"
# lastmod: {{ .Date }}
lastmod: "{{ dateFormat "2006-01-02" .Date }}"
author: ["Mugen"]
categories: ["cybersecurity"]
tags: ["tech", "cyber"]
subtitle: "je suis un sous titre"
description: "descriptopkfewkf"
weight: # 1 means pin the article, sort articles according to this number
slug: ""
draft: false # draft or not
comments: true
showToc: true # show contents
TocOpen: true # open contents automantically
hidemeta: false # hide information (author, create date, etc.)
disableShare: true	# do not show share button
showbreadcrumbs: true # show current path
cover:
    image: ""
    caption: ""
    alt: ""
    relative: false
---