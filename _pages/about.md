---
permalink: /
title: "Some cool stories"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Field research in Moscow region (June, 2019)
![My potato life🤷‍♀️](/images/penetrolog.jpg)

## Map of Talks
[A map of every location I've given a talk](https://mishagrol.github.io/talkmap.html).
======

## Sochi, Sirius
Machine Learning and Big Data Russian-Indian School in Sirius, Sochi (December, 2019)
![Sirius](images/sirius.jpg)
======



Poster presentation at SETAC YES'20 in Ghent, Belgium
======
Poster presentation at SETAC YES'20 in Ghent, Belgium
[Oil pollution🤷‍♀️](/images/ghent_for_site.png)
![Bioav-part-oil](/images/GH-OIL-BIOAV.png)
Investigations of the biological transformation of hydrocarbons in soils are based on the concept of limited bioavailability of hydrocarbons (as well as other hydrophobic organic pollutants) due to the distribution of hydrocarbons molecules within the soil matrix with the formation of various bonds with different components. Thus, the determination of the bioavailable fraction of hydrophobic organic pollutants is an important issue. 
Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
