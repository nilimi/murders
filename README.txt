We analyze US gun murder data collected by the FBI.

download-data.R - Downloads csv file to data directory

wrangle-data.R - Creates a derived dataset and saves as R object in rdas
directory

analysis.R - A plot is generated and saved in the figs directory.

*******************
My notes 

.rda (or .RData) - R Data

Had a hard time typing the download-data code. Was in forum, but also later found it in text. I did look for it before at the hyperlink the notes took me to, but couldn't find it. It's a lot of references and I wish they had pertinent tedious code in the notes.


The knitr package is used to compile R markdown documents.
The first time you click the "knit" button on the editor pane a pop-up window will prompt you to install packages, but after that is completed, the button will automatically knit your document.
github_document gives a .md file, which will give the best presentation on GitHub
Code

output: html_document 
output: pdf_document 
output: word_document
output: github_document

