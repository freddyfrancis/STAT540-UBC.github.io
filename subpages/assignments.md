---
title: "Course work"
output:
  html_document:
    includes:
      before_body: ../include/nav.html
      after_body: ../include/nothing.html
    toc: 3
---

You will have three individual assignments and one group project: 

- Ten in-seminar submissions (10 pts)
- One paper review (5 pts) 
- One practice assignment (5 pts)
- One statistics 2-part homework (30 pts)
- Final group project (50 pts) which contains multiple parts. 

<font color="red">**Deadlines are all by 11.59 pm of the due date**</font>

For help on your homework mechanics, please see this list of [assignment tips](assignment_tips.html) 

## Practice assignment
This is a warm-up for your future assignment. Once you have completed it, you will have set-up for the class and have a better understanding of how to set up your repository, pushing files to GitHub, writing markdown, and using R to do simple analyses. 

Go to [the practice assignment](https://github.com/STAT540-UBC/STAT540-UBC.github.io/blob/master/homework/practice_assignment/practice_assignment.md) and start now! 

Deadline: <span style="color: red">**Jan 17, 2018**</span> 

--------------

## Paper review 
Each student should review [this paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4405555/) in a 450-650 word summary/report. The summary should include: 

1. A brief review of the goal, findings and conclusion of the paper. 
2. A list (or mentioning) of the related datasets/databases and data types used in the study. In the case of datasets, provide some details of the data matrix and meta data.
3. A brief review of the analytical steps in the paper with more details on some selected parts which are relevant to the course materials. *You don't need to understand all of the analysis, but should be able to identify the key analysis/method used to answer the question the paper is intended to answer*
4. Some comments and critiques about the analytical steps, alternative suggestions or improvements. 

We have provided [**this guideline**](http://stat540-ubc.github.io/homework/paper\_critique/PRguideline.html) for this task. The material in the review **should not** be limited to merely answering the questions in the guideline, but rather using them to provide the required items listed above. Example paper reviews are also provided. Here's [another helpful resource](https://github.com/jtleek/readingpapers) on how to read a research paper

* Due date for the paper review: <span style="color: red">**Feb 22, 2018**</span>

**Delivery:** You should put your paper review files in your individual course repository in .md format (notice that you don't need to write it in .Rmd since you are not going to have any R code in it). You could edit .md files directly from github and therefore can write your full report there, but can also write it in your RStudio and then push it to your repository.

[example paper review](https://github.com/STAT540-UBC/STAT540-UBC.github.io/blob/master/homework/paper_critique/paperReviewMarjan.md)

--------------

## Analysis assignment 

This assignment will assess your understanding of the seminar and lecture materials. The assignment is split into two parts. Start early because this assignment will take time to be completed and perfected. Use the issues in the Discussion repo and the seminar time to ask questions. You will find most of the analysis workflow of the assignment in the seminar materials.

Questions for Part 1 can be downloaded [here](https://github.com/STAT540-UBC/STAT540-UBC.github.io/blob/master/homework/assignment/stat540_assignment_01_quality_control.md). Data for Part 1 is [here](https://github.com/STAT540-UBC/STAT540-UBC.github.io/tree/master/homework/assignment/data). 

- Due date for questions 1 - 3: <span style="color: red">**Mar 1, 2018**</span>
- Due date for questions 4 - 5: <span style="color: red">**Mar 22, 2018**</span>

--------------

## Final group project

### Deliverables

See the [**rubrics for project**](group_project_rubrics.html). 

### General principles

Identify a biological question of interest and a relevant dataset. Develop and apply a statistical approach that allows you to use the dataset to answer the question.

We assume the biological question and data fall in the general area of high-throughput, large-scale biological investigations *targetted by the course*. Beyond that, it is wide open: methylation, SNPs, miRNAs, CNVs, RNA-Seq, CHiP-Seq, gene networks, ... it's fair game. Avoid a dataset that doesn't have any/much quantitative data, i.e. contains only sequence or discrete data.

Note that definitive answers are not necessarily expected. Rather, aim to provide a critical appraisal of the data, the analytical approach, and the results. You will have to handle the competing pressures to "get it right" and "get it done". Shortcomings of the data, misfits between the data or the biological question and the statistical model, etc. are inevitable. Your goal is to identify such issues and discuss them critically, without becoming paralyzed. Demonstrate understanding of the statistical concepts and methods that are the foundation of your analytical approach.

We assume the analytical and computing task will have a substantial statistical component, probably enacted via R. So beware of a major analytical or computational undertaking that is, nonetheless, not statistical (example: constructing a database). Creating useful data visualizations can be absolutely vital and is arguably statistical, but your analysis should go beyond merely creating pretty pictures (but please do include some!). Key concepts, at least some of which should come up in your analysis:

 * the (hypothesized, probably artificial) data-generating model

 * background variation, variance, signal to noise ratio, estimates and their associated standard error

 * relationship between biological factors and experimental factors, apparent relative importance in terms of "explaining" observed data

 * attention to large-scale inference, e.g. control of family-wise error rate or false discovery rate
 
 
### Data considerations 

#### Appropriate use of data

If your project involves using unpublished data, ensure your plans are known to the data providers (e.g., your supervisors), and think about implications for publishing - are you are bringing the project team in as collaborators in effect? Are you planning to publish the results of your project, and if so who will be the co-authors? It is best to deal with these questions at the outset of the project.

#### Privacy of project data

The projects are not made public (other than being on a poster in the lobby of EOS for a few hours). The project report materials are loaded into Github, the secure site we use to manage the course. The course staff and instructors are the only people who have access to the projects other than the other members of the project group. The data used can be uploaded to the project, but this can limited or omitted if there are special concerns about privacy etc. - it's primarily the code and write-up about the results that needs to be provided for evaluation.

You can read Github's [security](https://help.github.com/articles/github-security/) and [privacy](https://help.github.com/articles/github-privacy-statement/) policies.

### Group makeup

Groups should have 4 to 6 members. We strongly encourage that groups be diverse in terms of backgrounds. In practice, this probably means the students should registered in a mix of programs/departments. All groups and group projects must be approved by the instructors.

--------------
    
## STAT 540 Homework Submission Instructions

**GitHub**
You all have a private repository in STAT540-UBC organization account, i.e., the repo `zz_lastname-firstnmae_STAT540_2018`. We assume that 

* You've already installed Git and (probably) a Git client.
* You can use command line Git and/or your Git client and perhaps even RStudio to push, pull, etc. to/from GitHub. 
* All your work is nicely organized in your repository. Your repository needs to include a clear top-level `README.md` that contains links to your work. This is the presentation of your repository and it helps others to find your work and contributions!

**IMPORTANT NOTE**: use the repository within the organization assigned to you to submit all your course work (i.e., the repo `zz_lastname-firstnmae_STAT540_2018`). Do not use branches or other repositories.
  
**Set-up your private GitHub repo for homework**

  * We're talking about the repo `zz_lastname-firstnmae_STAT540_2018` now.
  * Make a top-level directory for your assignment, e.g. `Homework`
    - We truly mean a [directory or "folder"](http://en.wikipedia.org/wiki/Directory_(computing)) -- NOT a [Git branch](http://git-scm.com/book/en/Git-Branching) or anything fancy like that! On your local computer, go to the directory where this Git repository lives. Make the 2 directories here.    
  * It is also nice to include a `README.md` inside each of the assignment and seminar directories. 
    - GitHub automatically renders all Markdown files into (pseudo-)HTML when you visit them in a browser. Whenever a *directory* in a repo is visited, if it contains a Markdown file called `README.md`, it will automatically be rendered, effectively serving as a landing or home page.

**R Markdown**

  * Write your homework in R Markdown. The file extension should be `.rmd`.
  * Recommendation: Create a skeleton of your report by starting with the Markdown file that creates the assignment itself! You can take some things away (unnecessary detail) and add others (R chunks) to morph this into your homework solution.
    - You'll have these files if you are using Git(Hub) to keep a current copy of the whole course repository. Or, from the links above, click on "Raw" to get raw Markdown and save to a local file.
    
**HTML**

  * Compile your homework to Markdown (file extension should be `.md`).
    - RStudio's "Knit HTML" button will do this. Your .md file is a intermediate file that can be read nicely on GitHub. 
    - Alternatively, use `knit2html()` from the `knitr` package in the R Console or in an R script.
    - To run from the shell or in a Makefile, use something like `Rscript -e "knitr::knit2html('hw01_lastname-firstnmae.rmd')"`
  * Notice that, by default, any figures created are placed into a `figures/` subdirectory. The intermediate Markdown file links to these and, therefore, requires them to present your full report. By default, the figures are base64 encoded and *embedded* into the HTML, which, therefore, is self-contained.

**What to put (or not put) into your Git(Hub) repository**

> This is rather specific to STAT 540 and may not necessarily reflect your workflow in the future and in other contexts.

  * Commit the main R markdown (`.rmd`) file that constitutes your solution. Commit early, commit often!
  * Do not commit the input data to your repository.
    - Locally, you are of course encouraged to keep the file in some logical place within the homework assignment's directory. But list the names of such data files in your top-level [`.gitignore` file](http://git-scm.com/docs/gitignore), so that Git ignores it. We do this so that TAs don't end up with 50 copies of the input data when they mark your work.
  * Commit the intermediate Markdown (`.md`) file and the figures stored in the `figures/` subdirectory.
    - Some purists would say intermediate and downstream products do NOT belong in the repo. After all, you can always recreate them from source, right? But here in reality, it turns out to be incredibly handy to have this in the repo.
  * Commit the end product HTML (`.html`) file.
    - See above comment re: version control purists vs. pragmatists.
  * Push closer to the submission date.
  * __Never ever__ edit the Markdown or HTML "by hand". Only edit the R Markdown source and then regenerate the downstream products from that.

**How to "turn in" your homework**

  * Make sure you have 
    - Saved all the files associated with your solution locally.
    - Committed those files to your local Git repository.
    - Pushed the current state of your local repo to GitHub.
  * Open an issue, link to the latest commit, tag us
    - Visit your private GitHub repository in a web browser
    - Just above the file list, look for the text "latest commit" followed by ten numbers and letters (called the revision SHA) and a clipboard icon
     - Click on the clipboard icon to copy the revision SHA to your clipboard
    - Click on "Issues", then on "New Issue". Name the issue "Mark homework of *your repository name*".
    - In the description of the issue, tag all TAs by including the text `@STAT540-UBC/ta_2018`, and paste the revision SHA. You can also include a link to the markdown file as well. 
     - Click "Submit new issue". You're done! Congratulations!

> If you're concerned that something hasn't gone right with the submission, send Emma, Julia and Ogan (emmagraham@cmmt.ubc.ca, julia.anstett@alumni.ubc.ca, ogan.mancarci@msl.ubc.ca) an e-mail with your assignment attached. **Note**: this is *only* an emergency back-up plan. We will pester and work with you until you eventually get it submitted via GitHub.

