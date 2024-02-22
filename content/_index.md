---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: hero
    demo: false # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Humans and Recommender Systems 
      subtitle: Towards a Mutual Understanding 
      text: |-
        Towards a Mutual Understanding
        <pre> 


















        </pre>
      advanced:
        css_class: fullscreen
    design:
      css_class: "light"
      background:
        text_color_light: true
        image: 
          filename: header.jpg
        filters:
          brightness: 0.5
  - block: markdown
    id: about
    content:
        title: About the Project
        text: |- 
          **Title:** Humans and Recommender Systems: Towards a Mutual Understanding  
          **Duration:** 01/09/2021-31/08/2024   
          **Funded by:** [FWF Austrian Science Fund](https://www.fwf.ac.at/en/)   
          **Total funding:** 599,686.50 EUR

          **Abstract**   
          Recommender systems (RS) are a central means for supporting users in dealing with information overload (e.g., in online shopping or on streaming platforms). Mostly, RS rely on some form of collaborative filtering, where recommendations are computed based on neighboring users or items. These approaches, however, neglect two important elements when modeling users and RS, leading to a mutual misunderstanding: firstly, RS are not able to capture the actual human decision-making that leads to choosing certain items and secondly, RS are hardly able to communicate the rationale behind recommendations. 

          In this project, we focus on music recommendations and strive to enhance the understanding of human decision-making underlying the choice of music in a given situational context. Moreover, we aim to advance the users' understanding for the decisions that lead to the recommendation of certain (sequences of) tracks. We believe that an increased understanding and communication between users and the system can contribute to improved user models and, thus, recommendation performance. A previously largely unexplored aspect will be the development of techniques for sequential recommendation strongly targeted at explanations and considering user feedback.

          Our research goals are as follows:
          - understanding and modeling user intent by approaching the task from two different perspectives: i. gaining a detailed understanding of user intent on the individual level through interviews to model the listening process, and ii. understanding intent by exploiting large-scale listening history data,
          - devising models for explanation of sequential recommendations and incorporating feedback in multi-faceted feature spaces, including dimensions of music content, listener intent, and listening context, and
          - researching consistency of theories (e.g., influence of personality on listening behavior) and our models created in a data-driven manner from large-scale user-generated data, and using respective findings to enhance our user and RS models.

          We adopt data- and hypothesis-driven methods; findings from both perspectives will be connected to existing theories and used to refine the models of user intent and explanations of recommendations. The developed models and techniques are evaluated by quantitative (also including beyond-accuracy measures) and qualitative means (e.g., structured interviews or task-driven user observations). 

          The project consortium is composed of five research institutions with complementary expertise: Eva Zangerle (University of Innsbruck, Department of Computer Science), Markus Schedl (Johannes Kepler University Linz), Peter Knees (Vienna University of Technology), Marcel Zentner (University of Innsbruck, Department of Psychology) and Michael Huber (University of Music and Performing Arts Vienna).
    design:
      columns: '2'
  - block: markdown
    id: members
    content:
      title: Members
      text: |- 
        * [Eva Zangerle](http://evazangerle.at), Universität Innsbruck (Principal Investigator)
        * [Michael Huber](https://www.mdw.ac.at/ims/team/michael-huber/), MDW Vienna (Co-Principal Investigator)
        * [Peter Knees](https://www.ifs.tuwien.ac.at/~knees/), TU Vienna (Co-Principal Investigator)
        * [Markus Schedl](http://www.mschedl.eu/), JKU Linz (Co-Principal Investigator)
        * [Marcel Zentner](https://www.uibk.ac.at/psychologie/fachbereiche/pdd/personality_assessment/mitarbeitende/zentner/), Universität Innsbruck (Co-Principal Investigator)
        * Richard Vogl, TU Vienna (PhD student)
        * Marta Moscati, JKU Linz (PhD student)
        * Andreas Peintner, Universität Innsbruck (PhD student)
        * Shahrzad Shashaani, TU Vienna (PhD student) 
        * Peer-Ole Jacobsen, Universität Innsbruck (student assistant)
        * Martin Bayer, Universität Innsbruck (student assistant)
      design:
        columsn: '2'
  - block: collection
    id: publications
    content:
      title: Recent Publications
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
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: Dr. Eva Zangerle
      text: 
      email: eva.zangerle@uibk.ac.at
      phone: 
      appointment_url: 'https://calendar.app.google/hcoKrALACU8awZQk6'
      address:
        street: Technikerstr. 21A
        city: Innsbruck
        postcode: '6020'
        country: Austria
        country_code: AT
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
