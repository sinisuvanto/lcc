"# README" 


# Language Crash Courses

Not qutie finished yet. But it shows how to get everything set up and running. 


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

Jekyll: 
```
Ruby version 2.5.0 or above, including all development headers (ruby version can be checked by running ruby -v)
RubyGems (which you can check by running gem -v)
```

Git: 
```
Git (Git version can be checked bu running git --version)
```

### Installing

A step by step series of examples that tell you how to get a development env running

Installing Jekyll 
```
The easiest way to run Jekyll is by using the RubyInstaller for Windows.

1. Download and Install a Ruby+Devkit version from RubyInstaller Downloads. Use default options for installation.
2. Run the ridk install step on the last stage of the installation wizard. This is needed for installing gems with native extensions. You can find additional information regarding this in the RubyInstaller Documentation
3. Open a new command prompt window from the start menu, so that changes to the PATH environment variable becomes effective. Install Jekyll and Bundler via: gem install jekyll bundler
4. Check if Jekyll installed properly: jekyll -v
```
See Jeykll documentation for detailed installation guides for your operating system: https://jekyllrb.com/docs/installation/


Installing Git 
```
1. Go to the official Git website: https://git-scm.com/
2. Download the latest version of Git (https://git-scm.com/downloads) and run the installer. Follow the Next and Finish prompts to complete the installation. The default options are pretty sensible for most users.
3. Open a Command Prompt (or Git Bash if during installation you elected not to use Git from the Windows Command Prompt).
4. Run the following commands to configure your Git username and email using the following commands: 
$ git config --global user.name "Your Name"
$ git config --global user.email "youremail@gmail.com"
```
See install this guide for a detailed installation guide based on your operating system: https://www.atlassian.com/git/tutorials/install-git


Cloning the project
```
Open your command prompt and clone the project with git clone.

Clone with HTTPS: 
$ git clone https://gitlab.com/1dirk/language-crash-courses.git

OR

Clone with ssh: 
$ git clone git@gitlab.com:1dirk/language-crash-courses.git

Git clone will create a directory called language-crash-courses

If you want another directory name specify the new directory name as an additional argument:
$ git clone https://gitlab.com/1dirk/language-crash-courses.git newdirectory 

That command does the same thing as the previous one, but the target directory is called newdirectory.

Now you have the project on yout computer.
```

Development
```
After you have cloned the project traverse into the directory in your command prompt.

On windows:
cd langauge-crash-courses

Next run this command to build your site and run it locally: 
$ bundle exec jekyll serve

jekyll serve builds the site and outputs a static site to a directory called _site
It rebuilds any time you make a change and runs a local web server at http://localhost:4000.

So everytime you make a change and save it you can se the result at http://localhost:4000. You just need to refresh the page. 

This is the way I have been developing the website. But before you push changes to GitLab you need to run the command:
$ bundle exec jekyll build 

This builds the site for production.

```

## Deployment

Add additional notes about how to deploy this on a live system
