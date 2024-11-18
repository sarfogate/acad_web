---
title: "Estimating the Probability of Historical Presence of Lead Service Lines with Firth Logistic Regression."

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Kaylee Pascarella
- admin 
- Rodney X. Sturdivant
- Amanda S. Hering

draft: false

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-09-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: 
 - "4"

# Publication name and optional abbreviated publication name.
publication: ''
publication_short: ''

abstract: The United States Environmental
Protection Agency is requiring any service line that is galvanized steel on the customer side that is or has
ever been downstream of a lead service line to be replaced. Thus, among those galvanized steel service lines
on the customer side, the city must identify upstream public service lines that are or were ever lead. The city
provided data on over 14,000 public service lines that are upstream of galvanized steel customer lines, of
which the material of 8,439 are known and 6,008 are unknown. Using the 8,439 observations as the training
set, we built logistic regression models to predict whether each public service line either (a) was never lead
or (b) is or had been lead. After performing a preliminary exploratory analysis, models were fit with up to
four predictors, namely (1) year built; (2) the material of the service line of the closest neighbor; (3) the
presence of another lead service line on the same block; and (4) the distance of the service line to the average
location of the known lead service lines. We find several models that perfectly predict the known lead service
lines in the training set, and we recommend using the model with all four predictors in it that also has a low
number of false positives. False positives would lead the city to replace a customer service line that does
not need to be replaced. Five-fold cross-validation and an assessment of the probabilities produced by the
model are used to validate it. When this model is fit on the training set and used to predict the 6,008 public
service lines of unknown material, we find that 306 of the lines are predicted to have lead with prediction
probabilities of 70% or greater. The 5,702 public service lines that are not predicted to not have lead have
prediction probabilities of never having lead that are 97.5% or higher. Thus, the city only needs to replace
the galvanized steel customer service lines that are downstream of these 306 public service lines. We find the
most important predictor in the model is “presence of another lead service line on the same block,” followed
by “the material of the service line of the closest neighbor.”
# Summary. An optional shortened abstract.
summary: ''

tags: []
categories: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Cox PH output: Reference level of categorical covariates denoted reference and
have estimated HR of 1'
  focal_point: Smart
  placement: 1
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

