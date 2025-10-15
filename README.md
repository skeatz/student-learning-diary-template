# Welcome to your new Fab Learning academy diary

This is an introduction file to your project folder. 
Contained in this project is your documentation website, read below to see what to do next.

Visit [fla.academany.org](https://fla.academany.org/) for class and other course information.

## Where to start editing

You have a few options to edit your markdown pages:

1. *(recommended)* Try our external editor at [editor.fabcloud.org](https://editor.fabcloud.org/).
2. There is also browser based Web IDE in your GitLab project (found under the blue "code" button). Read more about this editor [here](https://docs.gitlab.com/ee/user/project/repository/web_editor.html).
3. *(advanced)* You can clone this project to your computer using GIT and install MkDocs.

## About this project

* This website is built and published automatically using [GitLab CI](https://about.gitlab.com/gitlab-ci/), every time you edit the files in the docs folder
* The web page contents can be found in the `docs/` folder, written in markdown. Every file is a web page.
* To change the looks of your website, use the theme options found in the `mkdocs.yml` file or see the names of the available themes
* *(for advanced users)* If you want to start a website from scratch, you can delete everything in this repository and push your own static website.

## Project layout

    mkdocs.yml    # The site configuration file.
    docs/         # All site content/files should be in this folder.
        index.md  # The homepage.
        about.md  # This is the about bage
        files/    # Put files you'd like available in your site here (except videos)
        images/   # You can put your images in here
        diary/    # Sub folder with more pages

Read more about MkDocs at [mkdocs.org](http://www.mkdocs.org).


## Building mkdocs locally

To work locally on your computer with this project, you can start with the following the steps:

> Remember to setup your SSH keys to work locally, see [GitLab Docs](https://docs.gitlab.com/ee/gitlab-basics/create-your-ssh-keys.html)

1. Clone or download this project on your computer
	* Find the clone url at the top of your projects "overview" page
	* Run `git clone git@gitlab.fabcloud.org:your/project/path.git`
1. [Install](http://www.mkdocs.org/#installation) MkDocs on your computer
1. Preview your project: `mkdocs serve`, your site can be accessed under `localhost:8000`
1. Make an edit or add  a new file in the `docs/` folder
1. Push your changes to GitLab to automatically publish your changes
	* `git commit -m "Updated site"`
	* `git push main`


#### Git global setup

Do not forget to configure your local git environment, with same details used on Gitlab-Fabcloud.
```
git config user.name "You Name"
git config user.email "you@example.org"
```
