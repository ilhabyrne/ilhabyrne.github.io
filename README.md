# Welcome to my GitHub Pages repository

Below I have outlined some of the first steps that are required to build a website using GitHub Pages and Jekyll.

## Install dependencies
1. If using a mac, install homebrew using the terminal. Windows users will need ubuntu to access the terminal.
2. Next, install ruby and jekyll by following the instructions here: https://jekyllrb.com/docs/installation/macos/
3. Make sure you have a GitHub account. 
4. Have Github desktop installed on your computer.

## Setting up a GitHub page
On your web version of GitHub, create a repository for your site by following the instructions here: https://pages.github.com/. There is no need to create an index file at this point. Once you have done this, make sure to clone the repository locally.

## Getting started
On your local computer, use the command line to navigate to the folder that contains your newly created GitHub repository e.g., cd Documents/GitHub/ilhabyrne.github.io. Once in the repository, run the following command:
`jekyll .new --force`
This command will populate your repository with the base jekyll files need to make a website.

Then run the following command:
`bundle exec jekyll serve --watch`
This command allows you to edit files and have changes appear automatically to your website which will be visible at localhost:4000. 

## Building your website
Now you can start customizing your website! The config.yml file should be the first thing you look at as you will want to edit the title of your webpage, as well as personal links etc. You can get fancy later and change themes etc. The index.md file is also important as this is essential your home/landing page and you will want to change the details on there to suit your needs. New .md files can also be made to build new "pages" on your website. For example, as a scientist I might want a research page, CV page, and publications page. 



Note that all of the above steps are based on the tutorial run by gnorthrup - the video link is below. 


## Resources used
https://jekyllrb.com/docs/installation/macos/
https://www.youtube.com/watch?v=8NkxcaxRacA&ab_channel=CompBioSkillsSeminarUCBerkeley
https://brew.sh
