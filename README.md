# BrewLog

## Background
[Jekyll](https://github.com/jekyll/jekyll) is a static site generator that's perfect for GitHub hosted blogs.

[Jekyll-now](https://github.com/barryclark/jekyll-now) makes it easier to create your Jekyll blog, by eliminating a lot of the up front setup.

[BrewLog](https://github.com/benjholla/BrewLog) extends jekyll-now to create a version controlled homebrewing log/website.

- You don't need to touch the command line
- You don't need to install/configure ruby, rvm/rbenv, ruby gems :relaxed:
- You don't need to install runtime dependancies like markdown processors, Pygments, etc
- If you're on Windows, this will make setting up Jekyll a lot easier
- It's easy to try out, you can just delete your forked repository if you don't like it

In a few minutes you'll be set up with a minimal, responsive homebrew log like the one below giving you more time to spend on brewing.

![BrewLog Screenshot](/images/brewlog-screenshot.png "BrewLog Screenshot")

## Quick Start

### Step 1) Fork BrewLog to your User Repository

Fork this repo, then rename the repository to yourgithubusername.github.io.

Your Jekyll blog will often be viewable immediately at <http://yourgithubusername.github.io> (if it's not, you can often force it to build by completing step 2)

![Step 1](/images/step1.gif "Step 1")

### Step 2) Customize and view your site

Enter your site name, description, avatar and many other options by editing the _config.yml file. You can easily turn on Google Analytics tracking, Disqus commenting and social icons here too.

Making a change to _config.yml (or any file in your repository) will force GitHub Pages to rebuild your site with jekyll. Your rebuilt site will be viewable a few seconds later at <http://yourgithubusername.github.io> - if not, give it ten minutes as GitHub suggests and it'll appear soon

> There are 3 different ways that you can make changes to your blog's files:

> 1. Edit files within your new username.github.io repository in the browser at GitHub.com (shown below).
> 2. Use a third party GitHub content editor, like [Prose by Development Seed](http://prose.io). It's optimized for use with Jekyll making markdown editing, writing drafts, and uploading images really easy.
> 3. Clone down your repository and make updates locally, then push them to your GitHub repository.

![_config.yml](/images/config.png "_config.yml")
  
### Step 3) Publish your first brew

Edit `/_posts/2014-3-3-Hello-World.md` to publish your first blog brew. This [Markdown Cheatsheet](http://www.jekyllnow.com/Markdown-Style-Guide/) might come in handy.

![First Brew](/images/first-brew.png "First Brew")

> You can add additional brews in the browser on GitHub.com too! Just hit the + icon in `/_posts/` to create new content. Just make sure to include the [front-matter](http://jekyllrb.com/docs/frontmatter/) block at the top of each new blog brew and make sure the brew's filename is in this format: year-month-day-title.md

## Local Development

1. Install Jekyll and plug-ins in one fell swoop. `gem install github-pages` This mirrors the plug-ins used by GitHub Pages on your local machine including Jekyll, Sass, etc.
2. Clone down your fork `git clone git@github.com:yourusername/yourusername.github.io.git`
3. Serve the site and watch for markup/sass changes `jekyll serve`
4. View your website at http://0.0.0.0:4000
5. Commit any changes and push everything to the master branch of your GitHub user repository. GitHub Pages will then rebuild and serve your website.

## Features

✓ Command-line free _fork-first workflow_, using GitHub.com to create, customize and brew to your blog  
✓ Fully responsive and mobile optimized base theme (**[Theme Demo](http://jekyllnow.com)**)  
✓ Customized homebrewing theme (with version control!)
✓ Sass/Coffeescript support using Jekyll 2.0  
✓ Free hosting on your GitHub Pages user site  
✓ Markdown blogging  
✓ Syntax highlighting  
✓ Disqus commenting  
✓ Google Analytics integration  
✓ SVG social icons for your footer  
✓ 3 http requests, including your avatar  

✘ No installing dependancies  
✘ No need to set up local development  
✘ No configuring plugins  
✘ No need to spend time on theming  
✘ More time to brew/code other things ... wait ✓!