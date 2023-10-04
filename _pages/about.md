---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am Subhodip, a second year Ph.D student at **Rep**resentation **L**earning(**REPL**) Lab of [ECE department, IISc Bangalore](https://ece.iisc.ac.in/) advised by [Professor. Prathosh A.P.](https://sites.google.com/view/prathosh/home). My current research works fall in the domain of representation learning for vision tasks. Currently, I am looking at the deep neural networks through the lens of Privacy and Uncertainty.

**Research Motivation:**

Over the past century, the field of artificial intelligence (AI) has experienced remarkable progress, primarily driven by the aspiration to enable machines to learn in a manner akin to humans. This pursuit has been rooted in a fundamental question: How can machines be effectively trained to perform specific tasks? It seems like the answer is the optimization of some specific loss functions, typically relying on carefully curated datasets.

However, as we embark on the journey toward achieving artificial general intelligence (AGI), a stage where machines are trained on extensive and diverse datasets, the central question shifts from "how" to "what" these models are learning. It is no longer sufficient to focus solely on the mechanics of the learning process. Instead, we must delve into the profound inquiry of whether these AGIs possess intrinsic human values, such as privacy, safety, and fairness.

Furthermore, as we endeavor to endow AGI with human-like qualities, a critical attribute comes to the forefront—human awareness of the limitations of knowledge and the inherent uncertainty intertwined with it. Are these machines cognizant of their own uncertainty in decision-making, similar to human awareness, as our dependence on machine intelligence deepens? Can they promptly rectify their knowledge when exposed to erroneous information? Unfortunately, the answer to these inquiries is negative. These machines appear rigid and devoid of an understanding of the boundaries of their knowledge and the associated uncertainties.

To address these concerns, we must shift our focus from the "how" to the "what" i.e. what these models learn from the data. As machine intelligence assumes an ever-expanding role across diverse fields, we are compelled to confront the fundamental question of "what" precisely they are assimilating and comprehending from the information to which they are exposed.

**Research Interests:** I am curious to know what each data point contributes in the learning process and I beleive that privacy ([Diffential Privacy](https://en.wikipedia.org/wiki/Differential_privacy),[Privacy Attacks](https://arxiv.org/pdf/2007.07646.pdf)) can help understand what these deep networks learn from each datapoint and if needed how we can unlearn ([Machine Unlearning](https://arxiv.org/abs/2209.02299)). Also I am pretty fascinated by Distribution Free Uncertainty Estimations for deep neural networks. Below are some of the topics that I am interested in:
- **Privacy:** Machine Unlearning, Privacy Attacks, Differential Privacy.
I am creating a community on Machine Unleanrning as this is a fairly new area. Please join the group: [Machine-Unleanrning](https://discord.gg/YU9T5pvF) if interested.
- **Uncertainty:** Conformal Prediction and Calibration.
- **AI for Climate Change:** Novel Applications of representation learning for climate change problems. If you are interested to know more click here to join the group: [AI4ClimateChange](https://discord.gg/erxxGtY2)
  
<!--
A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
