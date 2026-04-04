---
title: 'Enterprise Design'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Jul 08 2022'
heroImage: '../../assets/blog-placeholder-3.jpg'
draft: false
---

Enterprise = Large company with complex organizational structure -> people problem

Design for Enterprise = catering to the many persona and people within the large company

How exactly?
1. View and action that adapts to the persona
A single table and view may be accessible to the many parties within the organization. How do you make that single view able to fulfill the JTBD for each parties accessing them? or do you create a new page for each party? Each approach must be chosen and handle by care

2. Strict but flexible access control
How do you provide a flexible role-based access control where you can configure easily who can access what, but set it as strict so only those that you configure can access and control according to their permission

Your UI must handle all cases, whether they have action permission or not, whether they have view access or not

3. Modularization
Very related to point 1, how can your UI and feature evolve according to configuration? If a certain feature is disabled, your design needs to handle all edge case and implications that rises from it.

4. Complex data management
Dribbble design annoys me as they always show the perfect data content for their design. In reality, data is ugly. How will your UI adapts to the messy data? Long names, empty data, foreign characters, are just some example that you need to handle.

---

Designing for enterprise means designing for a complex organizational structure, alongside its messy procedures and flow. Strong collaboration is necessary to survive in this fields.