---
type: "project" # DON'T TOUCH THIS ! :)
date: "2025-06-14" # Date you first upload your project.
# Title of your project (we like creative title)
title: "This is an example project page which serves as a template"

# List the names of the collaborators within the [ ]. If alone, simple put your name within []
names: [Wang Xinkai]

# Your project GitHub repository URL
github_repo: (https://github.com/wangxinkaitty/Wang_Xinkai_project/tree/main)

# If you are working on a project that has website, indicate the full url including "https://" below or leave it empty.
website:

# List +- 4 keywords that best describe your project within []. Note that the project summary also involves a number of key words. Those are listed on top of the [github repository](https://github.com/PSY6983-2021/project_template), click `manage topics`.
# Please only lowercase letters
tags: [project, github, markdown, brainhack]

# Summarize your project in < ~75 words. This description will appear at the top of your page and on the list page with other projects..

summary: "An attempt to analyze Chiang 2020 using only antonym contrary analogies instead of all analogy categories"

# If you want to add a cover image (listpage and image in the right), add it to your directory and indicate the name
# below with the extension.
image: ""
---
<!-- This is an html comment and this won't appear in the rendered page. You are now editing the "content" area, the core of your description. Everything that you can do in markdown is allowed below. We added a couple of comments to guide your through documenting your progress. -->

## Project definition

### Background

Inspired by the [Recurse Centre](https://www.recurse.com/) initiative (formally known as the "hacker school"), Brainhack School was established in 2018 with the mission to train students from multidisciplinary backgrounds to a panoply of reproducible tools for neural data science, using a project-based approach. Following an initial 3-weeks long pilot, a 4th week was added with an intensive bootcamp, so that students could choose what tools to learn more deeply in their projects. As the course became integrated in standard curriculum at different universities, the formula seemed to be working. In order to streamline the different stages of the project, some standard template and milestones needed to be incorporated in a github-based workflow. The "project template" project (which is also our first BHS meta-project) aims at establishing such a standardized template. You can check the following [video](https://youtu.be/PTYs_JFKsHI) where Pierre Bellec gives an overview of the Brainhack school.

<iframe width="560" height="315" src="https://www.youtube.com/embed/PTYs_JFKsHI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Tools

Here are the tools I used:

WSL Docker, Git, Github, Visual Studio Code, Ubuntu, Jupyter Notebook

### Data

The dataset used for this project is sourced from OpenNeuro and available at (https://openneuro.org/datasets/ds003094/versions/1.0.0). The relevant paper by Chiang et al 2020 is available at (https://reasoninglab.psych.ucla.edu/wp-content/uploads/sites/273/2021/04/005.Chiang_etal.JOCN_.pdf).

### Deliverables

Deliverable 1: Preprocessed Data of 16 Subjects

Deliverable 2: Project Code

Deliverable 3: Functionally Connectivity Graph

## Results

### Progress overview

The project was swiftly initiated by P Bellec, based on the existing template created in 2019 by Tristan Glatard and improved by different students. It was really not that hard. Community feedback is expected to lead to rapid further improvements of this first version.

### Tools I learned during this project

 * **Meta-project** P Bellec learned how to do a meta project for the first time, which is developping a framework while using it at the same time. It felt really weird, but somehow quite fun as well.
 * **Github workflow-** The successful use of this template approach will demonstrate that it is possible to incorporate dozens of students presentation on a website collaboratively over a few weeks.
 * **Project content** Through the project reports generated using the template, it is possible to learn about what exactly the brainhack school students are working on.

### Results

#### Deliverable 1: report template

You are currently reading the report template! I will let you judge whether it is useful or not. If you think there is something that could be improved, please do not hesitate to open an issue [here](https://github.com/PSY6983-2021/project_template/issues/) and let us know.

#### Deliverable 2: project gallery

You can check out the [2020 BrainHack School project gallery](https://psy6983.brainhackmtl.org/project/)

##### ECG pupilometry pipeline by Marce Kauffmann

The repository of this project can be found [here](https://github.com/mtl-brainhack-school-2019/ecg_pupillometry_pipeline_kaufmann). The objective was to create a processing pipeline for ECG and pupillometry data. The motivation behind this task is that Marcel's lab (MIST Lab @ Polytechnique Montreal) was conducting a Human-Robot-Interaction user study. The repo features:
 * a [video introduction](http://www.youtube.com/watch/8ZVCNeX42_A) to the project.
 * a presentation [made in a jupyter notebook](https://github.com/mtl-brainhack-school-2019/ecg_pupillometry_pipeline_kaufmann/blob/master/BrainHackPresentation.ipynb) on the results of the project.
 * Notebooks for all analyses.
 * Detailed requirements files, making it easy for others to replicate the environment of the notebook.
 * An overview of the results in the markdown document.

##### Other projects
Here are other good examples of repositories:
- [Learning to manipulate biosignals with python](https://github.com/mtl-brainhack-school-2019/franclespinas-biosignals) by François Lespinasse
- [Run multivariate anaylysis to relate behavioral and electropyhysiological data](https://github.com/mtl-brainhack-school-2019/PLS_PV_Behaviour)
- [PET pipeline automation and structural MRI exploration](https://github.com/mtl-brainhack-school-2019/rwickens-sMRI-PET) by Rebekah Wickens
- [Working with PSG [EEG] data from Parkinson's patients](https://github.com/mtl-brainhack-school-2019/Soraya-sleep-data-in-PD-patients) by Cryomatrix
- [Exploring Brain Functional Activation in Adolescents Who Attempted Suicide](https://github.com/mtl-brainhack-school-2019/Anthony-Gifuni-repo) by Anthony Gifuni

#### Deliverable 3: Instructions

 To be made available soon.

## Conclusion and acknowledgement

The BHS team hope you will find this template helpful in documenting your project. Developping this template was a group effort, and benefitted from the feedback and ideas of all BHS students over the years.

You can also make submit your project to neurolibre https://neurolibre.org/. It is a preprint server for interactive data analyses. It is tailored for publishing interactive neuroscience notebooks that can seamlessly integrate data, text, code and figures.The submission instructions can be found here https://docs.neurolibre.org/en/latest/index.html and the jupyter book docs there https://jupyterbook.org/intro.html.
