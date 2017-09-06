# 2017-09-Amherst-STAT495

This is the GitHub organization page for Amherst College [STAT/MATH 495 Advanced Data Analysis (Fall 2017)](https://www.amherst.edu/academiclife/departments/courses/1718F/STAT/STAT-495-1718F). Whereas the content and syllabus are on the course webpage <https://rudeboybert.github.io/STAT495/>, this organization contains the problem sets.

## Problem set submission process

The typical work flow for a problem set is:

* The instructor will post a skeleton outline of each problem set in its own *repository*, for example `PS01`. This repository will contain the necessary data files and a template R Markdown file.
* Students will *fork* (i.e. make a copy of) the repository to their own GitHub account.
* Students will *clone* (i.e. download) this forked repository as an RStudio project on their own machine.
* Students will complete the problem set on their own machine.
* Students will *commit* and *push* (i.e. upload) their work to the forked copy of the repository in their own GitHub account.
* Students will submit their work via *pull request*. This is a request to the owner of the master copy of the repository (in this case the instructor) to inspect and merge the proposed changes.
* The instructor will look at each individual student's pull requests and give feedback.
* The instructor will however not complete the final step of the typical pull request: they will not merge the proposed changes.

## Why are we doing this?

**Question**: Why did you set up this complicated scheme? Why not just give all students write-access to the repositories (by making them a collaborator) and allow them to submit individual files?

**Answer**: Because much of the collaboration that occurs in the open-source world centers around *pull requests* to propose changes/improvements. For example, many of the crowd-sourced changes/improvements to the [`ggplot2`](http://ggplot2.org/) R package for data visualization was done via one of (as of 2017-09-06) [610 pull requests](https://github.com/tidyverse/ggplot2/pulls?q=is%3Apr+is%3Aclosed). I would like to empower students to start taking their first steps of participation in this ecosystem.
