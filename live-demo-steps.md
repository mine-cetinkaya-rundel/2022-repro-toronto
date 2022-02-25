- open Rmd, with source editor
- knit
- also convert to visual editor

- change the file type to qmd, reopen
- output -> format: html
- change format: pdf, render, then change back
- render on save
- add citation: 10.1371/journal.pone.0090081
- add inline code for "bunch of" to nrow(penguins)
- yaml chunk options in the chunks
- add alt text to figure, "Scatterplot of bill length vs. flipper length for three species of penguins. The relationship is positive and moderately strong. The three species are identified on the plot with points with different colors and shapes, revealing three clusters."
- execute:
    echo: false
- back to echo: true, then autolink

format: 
  html:
    code-link: true

- insert image, add alt text
- tables -- before data "This package has two datasets: "

penguins

Size measurements for adult foraging penguins near Palmer Station, Antarctica

penguins_raw

Penguin size, clutch, and blood isotope data for foraging adults near Palmer Station, Antarctica


- tabsets for glimpse and tibble of data


- change to format: revealjs
- remove execute / echo to show they're off by default
- add a slide with two columns

- code line highlighting
	#| code-line-numbers: |3|5|7-12

- sidebar document outline, show print to pdf etc

- chalkboard

format: 
  revealjs:
    chalkboard: true




yan-ilumino