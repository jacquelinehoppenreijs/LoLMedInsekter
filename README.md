Lära och leva med insekter - contents

Project responsible: Peter Lampert
Author: Jacqueline Hoppenreijs

Project documents: 
- README file with user instructions
- Rmarkdown file with code for data analyses, visualisation and interpretation

Instructions for using Rmarkdown
- Download R from https://cran.r-project.org/bin/windows/base/ and install
- Download RStudio from https://posit.co/products/open-source/rstudio/ and install
- Download DataAnalysis_LoLMedInsekter.Rmd from Github and open in Rstudio


LoLMedInsekter.rmd is an Rmarkdown document. This type of document integrates code and text really nicely by alternating between text and chunks of code. 

Code chunks can be run by clicking the arrow on the right top corner of the individual chunk. 
If you want to run all code at once you can chose so in the "Run" menu at one of the top bars.

The code is written to work well with data in long format (as opposed to wide) and stored in basic Excel files (.xlsx extension). 

There are two types of text in the Rmarkdown file. The first is included in the code chunks, and explains what specific lines of code do. 
You can use this information to change the code, for example if you want to upload a new dataset or change the colours on a plot. 
The second type occurs outside of the code chunks and is used as headings to structure the document, 
or explains what data is included in plots or analyses and how the output can be interpreted. 

Rmarkdown helps create a readable type of output that doesn't require reading through all the code itself. 
You can create an output by "knitting" the Rmarkdown file in one of the top bars in Rstudio. 
The current settings will give you a Word document as output.
You can save the Word file with a name that reflects the data that you have analysed.