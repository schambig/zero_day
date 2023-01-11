<img align='right' src='https://user-images.githubusercontent.com/5713670/87202985-820dcb80-c2b6-11ea-9f56-7ec461c497c3.gif' width='100'><!--@schambig-->

[![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](http://commonmark.org)<!--@schambig-->
![GitHub last commit](https://img.shields.io/github/last-commit/schambig/holbertonschool-higher_level_programming)<!--@schambig-->
[![C|C](https://img.shields.io/badge/Repo-00%20commits-orange.svg)](https://sourcerer.io/schambig)<!--@schambig-->

# Git <!--@schambig-->

[Description](#description) • [Resources](#resources) • <!--@schambig-->[Additional Info](#additional-info) • [Project's Tasks](#projects-tasks)

---

## Description<!--@schambig-->

Git is a distributed version control system: tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows (thousands of parallel branches running on different systems).

Git was originally authored by Linus Torvalds in 2005 for development of the Linux kernel, with other kernel developers contributing to its initial development. Since 2005, Junio Hamano has been the core maintainer. As with most other distributed version control systems, and unlike most client–server systems, every Git directory on every computer is a full-fledged repository with complete history and full version-tracking abilities, independent of network access or a central server. Git is free and open-source software distributed under the GPL-2.0-only license.

This project is aimed to explore the functionalities of `Git` working in a local repository through the CLI and pushing the changes to the remote repository.

After this project I was able to [explain to anyone](https://fs.blog/feynman-learning-technique/):

* What is source code management
* What is Git
* What is GitHub
* What is the difference between Git and GitHub
* How to create a repository
* What is a README
* How to write good READMEs
* How to commit
* How to write helpful commit messages
* How to push code
* How to pull updates
* How to create a branch
* How to merge branches
* How to work as collaborators on a project
* Which files should and which files should not appear in your repo


## Resources<!--@schambig-->

Important concepts to help you understand this project:

* [Resources to learn Git](https://docs.github.com/en/get-started/quickstart/set-up-git)
* [About READMEs](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)
* [How to write a Git commit message](https://cbea.ms/git-commit/)
* [Learning branching](https://learngitbranching.js.org/?locale=es_AR)
* [Effective pull requests and other good practices for teams using GitHub](https://codeinthehole.com/tips/pull-requests-and-other-good-practices-for-teams-using-github/)

## Additional Info<!--@schambig-->

Install `git`

* If `git` is not already installed on your terminal:

```
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git
```

Basic usage

* At the end of this project you should be able to reproduce and understand these command lines:

```
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin main
```

## Project's Tasks<!--@schambig-->

All the required tasks will be inside the [git](https://github.com/schambig/zero_day/tree/master/git) folder of the project, you can read the requirements of every task in the table below:

| Task | Description |
| --- | --- |
| <pre>1. Repo-session</pre><!--@schambig--> | Create a new directory called `git` in your repo.<br>Make sure you include a not empty `README.md` in your directory:<br>• at the root of your repository<br>• AND in the directory `git`<br>And important part: Make sure your commit and push your code to Github - otherwise the Checker will always fail. |
| <pre>2. Coding fury road</pre><!--@schambig--> | For the moment we have an empty project directory containing only a `README.md`. It’s time to code!<br>• Create these directories at the root of your project: `bash`, `c`, `js`<br>• Create these empty files:<br>&nbsp;&nbsp;&nbsp;&nbsp;- `c/c_is_fun.c`<br>&nbsp;&nbsp;&nbsp;&nbsp;- `js/main.js`<br>&nbsp;&nbsp;&nbsp;&nbsp;- `js/index.js`<br>• Create a file `bash/best` with these two lines inside: `#!/bin/bash` and `echo "Best"`<br>• Create a file `bash/school` with these two lines inside: `#!/bin/bash` and `echo "School"`<br>• Add all these new files to git<br>• Commit your changes (message: “Starting to code today, so cool”) and push to the remote server |
| <pre>3. Collaboration is the base of a company</pre><!--@schambig--> | A branch is like a copy of your project. It’s used mainly for:<br>• adding a feature in development<br>• collaborating on the same project with other developers<br>• not breaking your entire repository<br>• not upsetting your co-workers<br>The purpose of a branch is to isolate your work from the main code base of your project and/or from your co-workers’ work.<br>For this project, create a branch `update_script` and in this branch:<br>• Create an empty file named `bash/98`<br>• Update `bash/best` by replacing `echo "Best"` with `echo "Best School"`<br>• Update `bash/school` by replacing `echo "School"` with `echo "The school is open!"`<br>• Add and commit these changes (message: “My personal work”)<br>• Push this new branch [Tips](https://docs.github.com/en/get-started/using-git/pushing-commits-to-a-remote-repository)<br>Perfect! You did an amazing update in your project and it’s isolated correctly from the main branch.<br>Ho wait, your manager needs a quick fix in your project and it needs to be deployed now:<br>• Change branch to `main`<br>• Update the file `bash/best` by replacing `echo "Best"` with `echo "This School is so cool!"`<br>• Delete the directory `js`<br>• Commit your changes (message: “Hot fix”) and push to the origin<br>Ouf, hot fix is done! |
| <pre></pre><!--@schambig--> |  |
| <pre></pre><!--@schambig--> |  |
| <pre></pre><!--@schambig--> |  |
<!-- <pre><br><br></pre> • <br>•-->
<br>•
<p align="center">
  <img alt="schambig" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=60&section=footer"/>
</p>
