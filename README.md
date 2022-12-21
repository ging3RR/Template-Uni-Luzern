# Template-Uni-Luzern

This is a template for all students of the University of Luzern who have to write their Master thesis and want to use RMarkdown to write it. I personally really recommend trying to write your thesis in RStudio. A few reasons are: flexibilty, customizability, fast workflow.

If you have never used Rmarkdown you will probably not understand most of what is going on. However getting into RMarkdown is really easy and you will understand most of the code after just a few hours. A big plus is if you know how LateX works (even better if you are good with it). I personally did not learn a lot about LateX, so there are many things I do not quite understand. It still worked for me so I am sure you can do it too :)

# Workflow

You can work on everything in RStudio, so there is no need to export graphics, copy code bits or results into a different programm. Also you can write your notes in the same window as you do your Analysis. I know not everyone needs this, but for me I have not been looking back for even 1 second. It is just so much faster and less frustrating.

# Generating the book

To render the book simply type *bookdown::render_book("index.Rmd", "bookdown::pdf_book")* into your command line. It will generate the PDF output into the *_book* folder.
Bookdown uses the numbering of the files to choose which one to put first (that can also be changed but for me it was fine like that). To create new chapters just create a new *.Rmd* file and name it with the next highest number.
If you need to get anything that is not in the root folder just add *foldername/* before your filename. 

The structure of this repository or generally how it works to generate the book is not from me. Most of it is from Thea Knowles https://bookdown.org/thea\_knowles/dissertating\_rmd\_presentation/.
A lot of important infos are also written down in the bookdown documentation https://bookdown.org/yihui/bookdown/. 



I hope this makes your life easier and you can use it to write your thesis in RStudio. It was a lot of work for me personally but definitely worth it. And since you do not have to start from the start like I do it should be even easier. Feel free to use, share, develop and change this repo as you like. If it helped you I would be happy to hear about it :D

# Good luck with your thesis!
