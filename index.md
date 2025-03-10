title: Luigi Di Natale
email: l.dinatale1182@gmail.com
description: >-  
  Senior Software Engineer with expertise in Java, Spring, React, PostgreSQL, and Go.
baseurl: ""
url: "https://luigidinatale.github.io"
github_username: luigidinatale

theme: minima

plugins:
  - jekyll-feed
  - jekyll-seo-tag
  - jekyll-sitemap

# Navigation
navbar:
  - name: "Home"
    link: "/"
  - name: "Resume"
    link: "/resume"
  - name: "Projects"
    link: "/projects"
  - name: "Contact"
    link: "/contact"

# Social Links
social:
  linkedin: "https://linkedin.com/in/luigidinatale"
  github: "https://github.com/luigidinatale"
  email: "l.dinatale1182@gmail.com"

# Collections
collections:
  projects:
    output: true
    permalink: /projects/:name/

# Pages
pages:
  - name: "index.md"
    content: |
      ---
      layout: default
      title: Home
      ---
      # Welcome to My Portfolio
      
      I'm **Luigi Di Natale**, a Senior Software Engineer specializing in Java, Spring, React, PostgreSQL, and Go. With experience leading cross-functional teams and optimizing software solutions, I am passionate about innovation and performance optimization.
      
      - [View my Resume](/resume)
      - [Explore my Projects](/projects)
      - [Contact Me](/contact)
  
  - name: "resume.md"
    content: |
      ---
      layout: default
      title: Resume
      ---
      # Resume
      
      ## Summary
      Results-driven Senior Software Engineer with a proven track record in designing, developing, and optimizing complex software solutions. Experienced in leading cross-functional teams, mentoring engineers, and collaborating with business stakeholders to deliver high-impact projects on time and within budget. Skilled in full-stack development, system architecture, and cloud-based solutions.
      
      ## Experience
      **Software Engineer III** - *Fanatics, Tampa, FL (June 2020 - Present)*
      - Led high-stakes projects, improving operational efficiency.
      - Designed and developed internal applications to streamline purchase order intake.
      - Built scalable solutions using Java, Spring, React, PostgreSQL, and Go.
      
      **Senior Software Engineer I** - *Mobiquity, Gainesville, FL (July 2016 – June 2020)*
      - Developed mobile and web applications using native and hybrid solutions.
      - Led teams and drove architectural decisions for multiple projects.
      - Updated and maintained legacy codebases.
      
      ## Education
      - **Bachelor of Science in Information Systems Management** - University of South Florida (2014)
      - **Associate of Arts** - St. Petersburg College (2012)
  
  - name: "projects.md"
    content: |
      ---
      layout: default
      title: Projects
      ---
      # Projects
      
      ## Order Validation Engine (OVE)
      - Designed and developed OVE for processing customer purchase orders.
      - Improved processing speed by 78%.
      - Technologies: Java, Spring, React, Go.
      
      ## Amazon Re:Invent App
      - Led a team to develop the mobile app for the Amazon Re:Invent 2017 conference.
      - Enhanced the attendee experience with innovative features.
      
      ## Wawa Mobile Application
      - Created a new user experience and introduced mobile ordering.
      - Revolutionized Wawa’s customer experience.
  
  - name: "contact.md"
    content: |
      ---
      layout: default
      title: Contact
      ---
      # Contact Me
      
      - **Email:** [l.dinatale1182@gmail.com](mailto:l.dinatale1182@gmail.com)
      - **LinkedIn:** [linkedin.com/in/luigidinatale](https://linkedin.com/in/luigidinatale)
      - **GitHub:** [github.com/luigidinatale](https://github.com/luigidinatale)
