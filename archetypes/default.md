---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
subtitle: ""
slug: "{{ index (split .File.Dir "/") 2 }}"
date: {{ .Date }}
lastmod: {{ .Date }}
draft: true
author: "linggang.tu"
description: ""
tags: []
categories: []

featuredImage: ""
featuredImagePreview: ""
---