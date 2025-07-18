---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-5-10
type: landing

sections:
  - block: hero
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Hugo Academic Theme
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: https://hugoblox.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/theme-academic-cv" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-


        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: Skills
  #   content:
  #     title: News
  #     text: ''
  #     # Choose a user to display skills from (a folder name within `content/authors/`)
  #     username: admin
    # design:
    #   columns: '1'
 
  - block: accomplishments
    id: news
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'News'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title:  Welcome to the EXPRESS@ISSTA workshop on June 28th!
          date_start: '2025-06-01'
          organization:
        - title:  Our paper "LLM-Powered Static Binary Taint Analysis" was accepted by TOSEM!
          date_start: '2024-12-30'
          organization:
    design:
      columns: '2'
  - block: experience
    id: exp
    content:
      title: Work Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      items:
        - title: Assistant Researcher
          company: Ang Group & Tsinghua University
          company_url: ''
          company_logo: ''
          location: China
          date_start: '2024-09-01'
          date_end: ''
    design:
      columns: '2'
  - block: experience
    content:
      title: Education Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: PhD in Cyberspace Security
          company:  University of Chinese Academy of Sciences
          company_url: 'https://scs.ucas.ac.cn/index.php/zh-cn/'
          company_logo: ''
          location: China
          date_start: '2018-09-01'
          date_end: '2024-07-01'
          # description: |2-
          #     Responsibilities include:
          #     * Analysing
          #     * Modelling
          #     * Deploying
        - title: B.Eng in Communication Engineering
          company:  Jilin University
          company_url: 'https://dce.jlu.edu.cn/'
          company_logo: ''
          location: China
          date_start: '2014-09-01'
          date_end: '2018-07-01'
        # - title: Professor of Semiconductor Physics
        #   company: University X
        #   company_url: ''
        #   company_logo: org-x
        #   location: California
        #   date_start: '2016-01-01'
        #   date_end: '2020-12-31'
        #   description: Taught electronic engineering and researched semiconductor physics.
    design:
      columns: '2'

      #     - course: PhD in Cyberspace Security
#       institution: University of Chinese Academy of Sciences
#       year: 2024.7
#     - course: B.Eng in Communication Engineering
#       institution:  Jilin University
#       year: 2018.7

  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  - block: collection
    id: featured
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: bug
    content:
      title: Vulnerabilitits
      subtitle: ''
      text: |-
        **Received 200+ confirmed vulnerabilities for embedded devices (e.g., vendor acknowledgement, CVE, CNVD, PSV), including from Cisco, Siemens, D-Link, and others.**
#          - CVE-2020-25242
#          - CVE-2022-20825
#          - ...
    design:
      columns: '2'

  - block: contact
    id: act
    content:
      title: Services
      subtitle: ''
      text: |-
        - **Committee:**
          - 2026: Shadow PC of EuroSys; AEC of NDSS
          - 2025: PC of EXPRESS@ISSTA, LLM4Sec@ICDM, ISPA; AEC of CCS 
        - **Journal Reviewer:**
          - CyberSecurity
          - Journal of Systems Architecture
          - IEEE Transactions on Software Engineering
          - Computer & Security
          - The Journal of Supercomputing
    design:
      columns: '2'

  - block: contact
    id: awards
    content:
      title: Honors & Awards
      subtitle: ''
      text: |-
          - 2024 AntStar of Ant Group
          - 2024 Outstanding Graduates of Beijing
          - 2024 Outstanding Graduates of University of Chinese Academy of Sciences
          - 2024 Outstanding Graduates of Institute of Information Engineering, CAS
          - 2023 National Scholarship 
          - 2023 Special Scholarship of Institute of Information Engineering, CAS
          - 2023 Merit Student Representative of University of Chinese Academy of Sciences
          - 2022 DataCon IoT Security Track Third Prize  
          - 2021 DataCon Email Security Track Runner-up Prize
          - 2018-2023 University of Chinese Academy of Sciences Scholarships
          - 2014-2018 Jilin University Scholarships
    design:
      columns: '2'

  - block: contact
    id: contact
    content:
      title: Contact
      #subtitle:
      # text: |-
    #     Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: ianianlpz@gmail.com



      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates


      coordinates:
        latitude: '30.2620'
        longitude: '120.1033'  
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      #form:
        #provider: netlify
        #formspree:
          #id:
        #netlify:
          # Enable CAPTCHA challenge to reduce spam?
          #captcha: false
    design:
      columns: '2'
---
