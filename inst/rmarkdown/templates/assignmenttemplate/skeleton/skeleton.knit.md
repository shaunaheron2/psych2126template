---
title             : "Your Main Title Goes Here"
short title : "Short title"
author: 
  - name          : "Put your name here"
    affiliation   : "1"
    corresponding : no    # Define only one corresponding author
    email         : "youremail@laurentian.ca"

affiliation:
  - id            : "1"
    institution   : "Laurentian University"
  - id            : "2"
    institution   : "PSYCH 2126: Research Methods"
    
date: "2024-02-03"

abstract: |
  One or two sentences providing a **basic introduction** to the field,  comprehensible to a scientist in any discipline.
  Two to three sentences of **more detailed background**, comprehensible  to scientists in related disciplines.
  One sentence clearly stating the **general problem** being addressed by  this particular study.
  One sentence summarizing the main result (with the words "**here we show**" or their equivalent).
  Two or three sentences explaining what the **main result** reveals in direct comparison to what was thought to be the case previously, or how the  main result adds to previous knowledge.
  One or two sentences to put the results into a more **general context**.
  Two or three sentences to provide a **broader perspective**, readily comprehensible to a scientist in any discipline.
  
  <!-- https://tinyurl.com/ybremelq -->
  
bibliography      : "r-references.bib"

floatsintext      : no
linenumbers       : no
draft             : no
mask              : no

figurelist        : yes
tablelist         : no
footnotelist      : no

classoption       : "man"
output            : papaja::apa6_pdf
---







# Introduction

Here you will add your **brief** literature review which should include a bit of background citing the papers you read in your initial research. You will also state your purpose, your hypotheses and justifications for them.

You can copy and paste your write up for these sections from Word or Google Docs directly into R Markdown. You can also write directly in R Markdown like I do, but I recommend the former in the beginning. Baby steps!

# Methods

Here you will report your study design, including sample size, independent and dependent variable(s) and any other important bits. <!-- 21-word solution (Simmons, Nelson & Simonsohn, 2012; retrieved from http://ssrn.com/abstract=2160588) -->

## Participants

You can use the participants and procedure headers if you like, or you can leave them out and just summarise them in the Methods section. These sections help organize a larger, thesis-length methods section but for our purposes they aren't necessary.

## Procedure

## Data analysis

Here you will cite the analysis you're going to conduct along with your descriptive statistics, ANOVA, correlations or whatever else you want to do.

\begin{table}
\centering
\begin{tabular}[t]{lrrrrrrr>{}r}
\toprule
  & Unique (\#) & Missing (\%) & Mean & SD & Min & Median & Max &   \\
\midrule
weight & 29 & 0 & \num{5.1} & \num{0.7} & \num{3.6} & \num{5.2} & \num{6.3} & \includegraphics[width=0.67in, height=0.17in]{D:/documents/R Projects/psych2126template/skeleton_files/figure-latex/hist_1f542439591e.pdf}\\
\bottomrule
\end{tabular}
\end{table}

```
## [1] "ctrl" "trt1" "trt2"
```






We used R [Version 4.3.2\; @R-base] and the R-packages *papaja* [Version 0.1.2\; @R-papaja], and *tinylabels* [Version 0.2.4\; @R-tinylabels] for all our analyses.

# Results

Here you will report your results.
You will produce a histogram out of your outcome variable and a visualization of your results. Note the examples below. The tutorials will help you achieve this. When you hand your paper in, follow the tutorial "Final Steps to Prepare Your Document" which will show you how to hide the code chunks and ONLY display the visuals in the final .pdf.

![(\#fig:unnamed-chunk-5)A Histogram](skeleton_files/figure-latex/unnamed-chunk-5-1.pdf) 


![(\#fig:unnamed-chunk-6)A Boxplot](skeleton_files/figure-latex/unnamed-chunk-6-1.pdf) 


![(\#fig:unnamed-chunk-7)Between Subject Boxplot](skeleton_files/figure-latex/unnamed-chunk-7-1.pdf) 

# Discussion


\newpage

# References

::: {#refs custom-style="Bibliography"}
:::
