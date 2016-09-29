---
layout: default
title: start page
---

This site demonstrates how to publish documentation for different products and components on Github pages. It juses the Jekyll framework together with an open-source theme.

# Products
This section lists all products and components and links to the relevant pages. The relevant information is collected from subfolders belonging to the corresponding products and components. 

{% include listProductsAndComponents %}


# Advanced Setup
In this showcase, the complete documentation is located in one repository. Using subtrees, it is possible to reference content from other repositories. The subtrees can be imported using scripts and will be automatically added, provided that some naming conventions are followed.


# FAQ
This section is a collection of FAQs that are stored in separate files (one file per issue.) The content is auto-collected from that collection. 

{% include listCollection collection="doc-troubleshooting" %}

