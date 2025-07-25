name: ✨ Feature request
description: Request a feature you'd like to see in SN!
title: "feature request"
labels: [feature]
body:
  - type: markdown
    attributes:
      value: |
        We're always looking for suggestions on how we could improve SN!
  - type: textarea
    attributes:
      label: Describe the problem you're trying to solve
      description: |
        Is your feature request related to a problem? Add a clear and concise description of what the problem is.
    validations:
      required: true
  - type: textarea
    attributes:
      label: Describe the solution you'd like
      description: A clear and concise description of what you want to happen.
    validations:
      required: true
  - type: textarea
    attributes:
      label: Describe alternatives you've considered
      description: |
        A clear and concise description of any alternative solutions or features you have considered.
  - type: textarea
    attributes:
      label: Additional context
      description: |
        Add any other additional context or screenshots about the feature request here.