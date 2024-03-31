---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing


sections:

  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  
  # SKILLS
  
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  
  
  # EXPERIENCE
  
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: National Director of Real Sector Policies
          company: Ministry of Economy and Finance
          company_url: 'https://www.finanzas.gob.ec/'
          company_logo: 
          location: Quito - Ecuador
          date_start: '2022-11-23'
          date_end: '2023-12-18'
          description: |2-
              Responsibilities include:

              * Prepare economic policy proposals for the real sector.
              * Coordinate the development of climate finance instruments.
              * Develop newsletters and current situation reports for the Real Sector.
              * Prepare reports for the monitoring and execution of Social Spending.

        - title: General Technical Coordinator
          company: Social Registry Unit
          company_url: 'https://www.registrosocial.gob.ec/'
          company_logo: 
          location: Quito - Ecuador
          date_start: '2021-03-16'
          date_end: '2022-10-16'
          description: |2-
              Responsibilities include:

              * Lead and verify the design of methodologies for identifying families that live under poor conditions.
              * Coordinate the development of Social Registry information updating models.
              * Lead the design of methodologies for interconnectivity and information exchange.

        - title: Advisor to the Executive Board
          company: Social Registry Unit
          company_url: 'https://www.registrosocial.gob.ec/'
          company_logo: 
          location: Quito - Ecuador
          date_start: '2021-09-21'
          date_end: '2022-03-15'
          description: |2-
              Responsibilities include:

              * Define strategies oriented to scientific and social research projects.
              * Develop socioeconomic projects and plans.
              * Coordinate activities with the technical directorates.

        - title: Teaching assistant
          company: EAFIT University
          company_url: 'https://www.eafit.edu.co/'
          company_logo: 
          location: Medellín - Colombia
          date_start: '2021-05-01'
          date_end: '2022-06-15'
          description: |2-
              Responsibilities include:

              * Advanced Microeconomics I for graduate students in Economics.
              * Review, explain and solve exercises proposed by the professor.
              * Review of class material.

        - title: Assistant professor
          company: EAFIT University
          company_url: 'https://www.eafit.edu.co/'
          company_logo: 
          location: Medellín - Colombia
          date_start: '2021-03-01'
          date_end: '2022-06-15'
          description: |2-
              Responsibilities include:

              * General Macroeconomics for undergraduate students of the School of Management.
              * Preparation of class material in accordance with planning.
              * Elaboration and revision of assignments, lessons and exams.

        - title: Research assistant
          company: EAFIT University
          company_url: 'https://www.eafit.edu.co/'
          company_logo: 
          location: Medellín - Colombia
          date_start: '2020-02-01'
          date_end: '2021-06-15'
          description: |2-
              Responsibilities include:

              * Special and weekly reports describing current economic issues in Colombia.
              * Degree work: Effects of the productive transformation and energy transition measured through a CGE model. Advisors: Álvaro Hurtado and Jesús Botero.
              * Development and uses of CGE, DSGE, ML models.

        - title: Research assistant 
          company: Escuela Superior Politécnica del Litoral (ESPOL University)
          company_url: 'https://www.espol.edu.ec/es'
          company_logo: 
          location: Guayaquil - Ecuador
          date_start: '2019-05-15'
          date_end: '2020-01-15'
          description: |2-
              Responsibilities include:

              * Research assistant to Professor Leonardo Sánchez Aragón, PhD.
              * Analysis of agricultural statistics from the microdata of the ESPAC survey. Spatial Statistics Review
              * Initial research on the effects of contagion of the fungus Fusarium RT4 in a Network of Banana farmers.
              * Participation in the creation of a database for the construction of a Network on top 5 magazine authors.





    design:
      columns: '2'


  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Ongoing Learning'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:

        - certificate_url: https://github.com/megonzau/megonzau-github.io/blob/main/content/authors/admin/Diploma%20U%20Chile.pdf
          date_end: '2022-12-03'
          date_start: '2022-09-26'
          description: 'The Diploma is taught at the Pontificia Universidad Católica, in Santiago, Chile, by J-PAL affiliated professors and academics at UC. The program consists of three courses: Impact evaluation methods, Evidence and policy, and Implementation of an impact evaluation.'
          icon: 
          organization: Pontificia Universidad Católica de Chile ‑ JPAL 
          organization_url: https://educacioncontinua.uc.cl/
          title: Diploma in Impact Evaluation of Public Policy and Social Programs
          url: 'https://www.povertyactionlab.org/page/diploma-impact-evaluation-public-policy-and-social-programs?lang=fr'


        - certificate_url: 
          date_end: ''
          date_start: '2021-01-01'
          description: In this edition, we study a microeconomic approach. In particular, we will put emphasis on Climate-Smart Agriculture (CSA), which encompasses different agricultural practices that aim to sustainably increase productivity, enhance resilience, and reduce greenhouse gases (GHG) emissions.
          icon: 
          organization: EAFIT University 
          organization_url: https://www.eafit.edu.co/
          title: Summer School of the Economics of Climate Change and Climate Policy
          url: 

          
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          icon: datacamp
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in R'
          url: ''
    design:
      columns: '2'




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





  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation




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
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Talk things over a cup of coffee
      # Contact (add or remove contact options as necessary)
      email: marcosgonza.eau@gmail.com
      phone: 
      appointment_url: 
      address:
        street: December 6th Avenue
        city: Quito
        region: Pichincha
        postcode: '170501'
        country: Ecuador
        country_code: EC
      directions: 
      office_hours:
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '-0.188718'
        longitude: '-78.482163'  
      contact_links:
        # - icon: twitter
        #   icon_pack: fab
        #   name: DM Me
        #   link: 'https://twitter.com/Twitter'
        # - icon: skype
        #   icon_pack: fab
        #   name: Skype Me
        #   link: 'skype:echo123?call'
        # - icon: video
        #   icon_pack: fas
        #   name: Zoom Me
        #   link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: false
      # Email form provider
      form:
        provider: 
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---
