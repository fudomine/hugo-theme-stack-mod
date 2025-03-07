---
title: "{{ replace .Name "-" " " | title }}"
description: 
date: {{ .Date }}
image: https://picsum.photos/800/600.webp?random={{ substr (md5 (.Date)) 4 8 }}
math: 
license: 
hidden: false
comments: true
draft: true
---