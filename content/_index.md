---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: markdown
    id: welcome
    content:
      title: Resources on multi-method evaluation in research and development of interactive intelligent systems
      text: |-
            A single evaluation method or measure is not able to evaluate all relevant aspects in a complex setting where a multitude of stakeholders are involved. We reason that employing a multi-method evaluation, where multiple evaluation methods or measures are combined and integrated, allows for getting a richer picture and prevents blind spots in the evaluation outcome.
            
            {{% box note %}}
            We advocate for multi-method evaluation. On this website, we collect resources that help to apply multi-method evaluation in research and development.
            {{% /box %}}
            
            This collection is meant to grow over time and we are happy to share your resources and discuss best practices. Don't hesitate to [contact us](#contact)!
  - block: collection
    id: news
    content:
      title: Latest News
      filters:
        folders:
          - post
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: card
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true
  - block: markdown
    id: about
    content:
        title: About
        text: |-
            {{% box cv %}}
            ## Christine Bauer

            ![Photo of Christine Bauer](chb.jpg)

            Christine Bauer is a Professor of Interactive Intelligent Systems at the Department of Artificial Intelligence and Human Interfaces (AIHI) at the University of Salzburg, Austria. Her research activities center on interactive intelligent systems. Thereby, she takes a human-centered perspective, where technology follows humans’ and the society’s needs.
            Her research and teaching activities are driven by her interdisciplinary background. She holds a Doctoral degree in Social and Economic Sciences, a Master degree in Business Informatics, and a Diploma degree in International Business Administration. In addition, she pursued studies in jazz saxophone.
            She has co-authored more than 130 papers, and holds several best paper awards as well as awards for her reviewing activities. Furthermore, she is an Elise Richter laureate and received a grant for the project “Fine-grained Culture-aware Music Recommender Systems” (2017--2020) sponsored by Austrian Science Fund (FWF). 
            {{% /box %}}   

            {{% box cv %}}
            ## Eva Zangerle

            ![Photo of Eva Zangerle](ez.jpg)

            Eva Zangerle is an Associate Professor at the University of Innsbruck at the research group for Databases and Information Systems (Department of Computer Science), Austria. She earned her master’s degree in Computer Science at the University of Innsbruck and subsequently pursued her Ph.D. from the University of Innsbruck in the field of recommender systems for collaborative social media platforms. Her main research interests are within the fields of music recommender systems, social media analysis and information retrieval. Over the last years, she has combined these three fields of research and investigated context-aware music recommender systems based on data retrieved from social media platforms aiming to exploit new sources of information for recommender systems. She was awarded a Postdoctoral Fellowship for Overseas Researchers from the Japan Society for the Promotion of Science allowing her to make a short-term research stay at the Ritsumeikan University in Kyoto.
            {{% /box %}}
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2' 
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: citation
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true
  - block: collection
    id: events
    content:
      title: Events
      filters:
        folders:
          - events
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: card
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true
  - block: markdown
    id: contact
    content:
      title: Contact
      text: |-
        Christine Bauer\
        University of Salzburg\
        Faculty of Digital and Analytical Sciences\
        Department of Artificial Intelligence and Human Interfaces (AIHI)\
        christine.bauer [at] plus.ac.at\
        https://christinebauer.eu
        
        Eva Zangerle\
        University of Innsbruck\
        Department of Computer Science\
        Databases and Information Systems\
        eva.zangerle  [at]  uibk.ac.at\
        https://www.evazangerle.at
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
---
