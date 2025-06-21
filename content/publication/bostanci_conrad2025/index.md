---
title: "Integrating Agent-Based and Compartmental Models for Infectious Disease Modeling: A Novel Hybrid Approach"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Inan Bostanci
- Tim Conrad

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2025-01-31T00:00:00Z"
doi: "https://doi.org/10.18564/jasss.5567" #test this

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In Journal of Artificial Societies and Social Simulation
publication_short: In JASSS

abstract: "This study investigates the spatial integration of agent-based models (ABMs) and compartmental models for infectious disease modeling, presenting a novel hybrid approach and examining its implications. ABMs offer detailed insights by simulating interactions and decisions among individuals but are computationally expensive for large populations. Compartmental models capture population-level dynamics more efficiently but lack granular detail. We developed a hybrid model that aims to balance the granularity of ABMs with the computational efficiency of compartmental models, offering a more nuanced understanding of disease spread in diverse scenarios, including large populations. This model spatially couples discrete and continuous populations by integrating an ordinary differential equation model with a spatially explicit ABM. Our key objectives were to systematically assess the consistency of disease dynamics and the computational efficiency across various configurations. For this, we evaluated two experimental scenarios and varied the influence of each sub-model via spatial distribution. In the first, the ABM component modeled a homogeneous population; in the second, it simulated a heterogeneous population with landscape-driven movement. Results show that the hybrid model can significantly reduce computational costs but is sensitive to between-model differences, highlighting the importance of model equivalence in hybrid approaches. The code is available at: git.zib.de/ibostanc/hybrid_abm_ode."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. #Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed #ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below) (Page does not deploy if I do this)
links:
# - name:Link
#   url: https://www.tandfonline.com/doi/full/10.1080/09644016.2022.2048556

url_pdf: 'http://jasss.soc.surrey.ac.uk/28/1/5.html'
url_code: 'https://git.zib.de/ibostanc/hybrid_abm_ode'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---


