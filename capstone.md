---
layout: topic
title: Capstone exercise
---

### Using an Rmd file, create a short analysis report of the  dataset.

Feel free to collaborate!


1. Write an Rmd script to load the Portal data file and make a box plot of
   weight by sex for male and female animals (male and female only; discard data
   for other sexes). Make sure you load any packages (dplyr, etc.) that you may
   need to create this. Describe the results, including the mean of each group,
   using markdown text.
2. Make a histogram of all hindfoot lengths using the default bin widths, then a
   second one with narrower bin widths.
3. Choose three species. Make a scatterplot of weight (on x) vs hindfoot length,
   with the points colored by species id.
4. For the species code `DM`, use dplyr to calculate the total number of counts
   per year for each plot type.
5. Using the data frame you just created, plot the counts (of the species "DM")
   over time as line graphs faceted by plot type.
