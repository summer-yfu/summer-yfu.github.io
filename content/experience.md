---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: me
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: skills-cloud
    id: skills
    content:
      title: Skills
      skills:
        - name: "Full-Stack Development"
          items:
            - "Python, C/C++, C#, TypeScript, JavaScript"
            - "REST APIs, React, Next.js, Node.js"

        - name: "AI Systems & Agent Frameworks"
          items:
            - "Large Language Models (LLMs), RAG, Prompt Engineering"
            - "LangChain, LangGraph, Multi-Agent Systems"

        - name: "Machine Learning"
          items:
            - "PyTorch, TensorFlow"
            - "NumPy, Pandas, Scikit-learn"
            - "Neural Networks, Transformers, Deep Learning"

        - name: "Databases"
          items:
            - "PostgreSQL, MySQL, MongoDB"

        - name: "Infrastructure & DevOps"
          items:
            - "Docker, AWS, Git"
            - "CI/CD, Linux"

        - name: "Game Development"
          items:
            - "Unity, Unreal Engine, Godot, Blender"
    design:
      columns: "1"
  # - block: skills-cloud
  #   id: skills
  #   content:
  #     title: Skills
  #     groups:
  #       - title: Languages
  #         items:
  #           - label: C
  #             icon_class: devicon-c-plain
  #           - label: C++
  #             icon_class: devicon-cplusplus-plain
  #           - label: Python
  #             icon_class: devicon-python-plain
  #           - label: Bash
  #             icon_class: devicon-bash-plain

  #       - title: Platforms & OS
  #         items:
  #           - label: Linux
  #             icon_class: devicon-linux-plain
  #           - label: AWS
  #             icon_class: devicon-amazonwebservices-plain-wordmark
  #           - label: IoT
  #             abbr: IoT

  #       - title: Tooling & CI/CD
  #         items:
  #           - label: Git
  #             icon_class: devicon-git-plain
  #           - label: GitHub
  #             icon_class: devicon-github-original
  #           - label: GitHub Actions
  #             icon_class: devicon-githubactions-plain
  #           - label: Jenkins
  #             icon_class: devicon-jenkins-plain

  #       - title: Protocols & Domains
  #         items:
  #           - label: HTTP
  #             abbr: HTTP
  #           - label: Device-to-Cloud Comms
  #             abbr: D2C

  #       - title: AI Tools
  #         items:
  #           - label: Claude Code
  #             abbr: ✳
  #           - label: Cursor
  #             abbr: ◈
  #           - label: Copilot
  #             icon_class: devicon-github-original
  #   design:
  #     columns: "1"
  # - block: resume-awards
  #   content:
  #     title: Awards
  #     username: me
  - block: resume-languages
    content:
      title: Languages
      username: me
---
