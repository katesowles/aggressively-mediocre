---
title: "{{ replace .Name "-" " " | title }}"
slug: "/{{ now.Format "2006-01-02" }}/{{ lower .Name | urlize }}"
date: {{ .Date }}
draft: true
tags:
  [
    "ADD",
    "ADHD",
    "anxiety",
    "career",
    "depression",
    "mental health",
    "neurodiversity",
    "personal",
    "software development",
  ]
---
