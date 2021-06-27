---
title: Mechanisms of Action Prediction Challenge

summary: We run a computational challenge to solicit solutions to the automatic classification of drugs based on their biological activity in human cells. Over 4,000 people joined the competition by submitting hundreds of computational approaches.  

tags:
- Deep Learning
- Drugs
- Healthcare
- Computational biology
- Crowdsourcing
- Open innovation 

date: "2021-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

# Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight

image:
  caption: Photo by es Pommier, Rozenn Josse, on Unsplash
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

---

This project was sponsored by the [Connectivity Map](https://clue.io), within the [Broad Institute of MIT and Harvard](www.broadinstitute.org), the [Laboratory for Innovation Science at Harvard (LISH)](www.lish.harvard.edu), and the [NIH Common Funds Library of Integrated Network-Based Cellular Signatures (LINCS)](www.nih.gov). The aim was to advance drug development through improvements to MoA prediction algorithms. The means were an open challenge hosted on the crowdsourcing platform [Kaggle](www.kaggle.com). Visit [the challenge's website](https://www.kaggle.com/c/lish-moa) for more information, data, and source codes. 

## What is the Mechanism of Action (MoA) of a drug? And why is it important?

In the past, scientists derived drugs from natural products or were inspired by traditional remedies. Very common drugs, such as paracetamol (acetaminophen) were put into clinical use decades before the biological mechanisms driving their pharmacological activities were understood. Today, with the advent of more powerful technologies, drug discovery has changed from the serendipitous approaches of the past to a more targeted model based on an understanding of the underlying biological mechanism of a disease. In this new framework, scientists seek to identify a protein target associated with a disease and develop a molecule that can modulate that protein target. As a shorthand to describe the biological activity of a given molecule, scientists assign a label referred to as mechanism-of-action or MoA for short.

## How do we determine the MoAs of a new drug?

One approach is to treat a sample of human cells with the drug and then analyze the cellular responses with algorithms that search for similarity to known patterns in large genomic databases, such as libraries of gene expression or cell viability patterns of drugs with known MoAs.

## What was the goal of this challenge?

In this competition, competitors had access to a unique dataset that combines gene expression and cell viability data for about 5,000 drugs. The data is based on a new assay that measures simultaneously (within the same samples) human cells’ responses to drugs in a pool of 100 different cell types (thus solving the problem of identifying ex-ante, which cell types are better suited for a given drug). The competitors also had access to MoA annotations for more than 5,000 drugs in this dataset.

The dataset was split into testing and training subsets. Hence, the task was to use the training dataset to develop an algorithm that automatically labels each case in the test set as one or more MoA classes ("multiple-label classification"). 

## How to evaluate the accuracy of a solution?

Based on the MoA annotations, the accuracy of solutions was evaluated on the average value of the logarithmic loss function applied to each drug-MoA annotation pair.

## Results 

The analysis of the results of this competition is in progress. 

