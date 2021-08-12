# Data Wrangling and Processing for Genomics

# Overview
Create an enviroment called  Genomics and install required packages for genomic analysis
packages to be used include fastqc for quality assesment of the reads.trimmomatic for trimming adapters from the reads.

# Background and Metadata	What data are we using?
We are going to use a long-term sequencing dataset from a population of Escherichia coli.

What is E. coli?
E. coli are rod-shaped bacteria that can survive under a wide variety of conditions including variable temperatures, nutrient availability, and oxygen levels. Most strains are harmless, but some are associated with food-poisoning.
 [Wikimedia](https://species.wikimedia.org/wiki/Escherichia_coli#/media/File:EscherichiaColi_NIAID.jpg) 

Why is E. coli important?
E. coli are one of the most well-studied model organisms in science. As a single-celled organism, E. coli reproduces rapidly, typically doubling its population every 20 minutes, which means it can be manipulated easily in experiments. In addition, most naturally occurring strains of E. coli are harmless. Most importantly, the genetics of E. coli are fairly well understood and can be manipulated to study adaptation and evolution.
The Data
The data we are going to use is part of a long-term evolution experiment led by Richard Lenski.

The experiment was designed to assess adaptation in E. coli. A population was propagated for more than 40,000 generations in a glucose-limited minimal medium (in most conditions glucose is the best carbon source for E. coli, providing faster growth than other sugars). This medium was supplemented with citrate, which E. coli cannot metabolize in the aerobic conditions of the experiment. Sequencing of the populations at regular time points revealed that spontaneous citrate-using variant (Cit+) appeared between 31,000 and 31,500 generations, causing an increase in population size and diversity. In addition, this experiment showed hypermutability in certain regions. Hypermutability is important and can help accelerate adaptation to novel environments, but also can be selected against in well-adapted populations.

To see a timeline of the experiment to date, check out this figure, and this paper Blount et al. 2008: Historical contingency and the evolution of a key innovation in an experimental population of Escherichia coli.


# Why is this experiment important?
# Assessing Read Quality	How can I describe the quality of my data?
# Trimming and Filtering	How can I get rid of sequence data that doesn’t meet my quality standards?
# Variant Calling Workflow	How do I find sequence variants between my sample and a reference genome?
# Automating a Variant Calling Workflow

