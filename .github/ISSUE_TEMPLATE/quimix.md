---
name: Quimix
about: Show off a cool color combo!
title: My Quimix
labels: quimix
assignees: ''

---

name: "Quimix Submission"
description: "Submit a cool color combo!"
title: "[Quimix] - <Quimix Name>"
labels: ["quimix", "enhancement"]
assignees: []

body:
  - type: markdown
    attributes:
      value: "## 🎨 Quimix Submission\nShare a cool color combo!"

  - type: input
    id: quimix-name
    attributes:
      label: "🇶 Quimix Name"
      description: "Give your color combo a cool name!"
      placeholder: "E.g., Neon Dream, Oceanic Glow"

  - type: textarea
    id: colors
    attributes:
      label: "🎨 Colors"
      description: "List your colors as hexcodes. (E.g., #ff5733)"
      placeholder: |
        - #ff0000
    validations:
      required: true

  - type: textarea
    id: description
    attributes:
      label: "📝 Description"
      description: "Describe the vibe or inspiration behind your Quimix!"
      placeholder: "This mix is inspired by a cyberpunk sunset..."
