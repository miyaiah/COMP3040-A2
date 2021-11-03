# Hosting a Markdown Resume on Github Pages
This project will walk you through the steps of hosting a resume as a website. In this example, we will write the file itself in the Markdown language, and utilize a program like HackMD as our Markdown editor. The file will be hosted on GitHub Pages, which uses Jekyll to convert your Markdown file into a nice-looking webpage. Your project should also incorporate ideas from Andrew Etter's book *Modern Technical Writing*. He gives great guidelines on making sure your writing is useful and practical.

## Getting Started
Hosting a resume on GitHub does not require you to download lots of complicated software. However, there are a few things you will need prior to starting this process.
#### Prerequisites 
* A Markdown editor to write your resume in
    * I like [HackMD](https://hackmd.io/) because it's online, but if that's not your thing, try downloading [Atom](https://atom.io/) instead 
* A resume written in Markdown
* A [GitHub](https://github.com/) account 

#### More Resources
* A basic tutorial on how to use Markdown [linked here](https://www.markdowntutorial.com/)
* [Jekyll's website](https://jekyllrb.com/)
    * Jekyll is a part of GitHub Pages so you do not need to download it for this project, but if you are interested in learning how exactly it works, I recommend trying to use it for hosting a static site locally. They also have a good tutorial on their website on how to do this.
* [*Modern Technical Writing* by Andrew Etter](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) as an ebook on Amazon

## Instructions
In these steps, we will be creating a static website. It will be hosted on GitHub Pages and be generated using Jekyll. Etter highlights the benefits of static sites in his book, specifically mentioning their simplicity and stability. They require no dynamic generation and do not demand much from a server. You can even host one locally! Most relevant, as I hope you will take this away from this project, they are very easy to set up.
### Part 1: Creating a GitHub repository
a. Setting up a new repository
1. Sign into GitHub.
2. Navigate to your repositories and select the 'New' button.  
OR  
You can go to the '+' menu in the top right corner of the page, and select 'New repository'.  

![new repo](https://i.imgur.com/ol4vrTb.jpg)

3. Enter the name of your repository. To ensure GitHub makes the static site with the URL as simply the name of your repository, call it **your_username_here.github.io**

![set up repo](https://i.imgur.com/wv7FAe2.png)

4. Set your repository to public if you wish to share your site with others.
5. Press 'Create Repository'.  

b. Adding your resume
1. Select to upload an existing file. We will use the Markdown file of our resume that we have already written. *Your resume file needs to be called **index.md**.* This is because GitHub recognises the file called 'index' as the homepage of the static site.
 
![add file to new repo](https://i.imgur.com/7nMdCym.jpg)

2. Commit your changes.  

c. Adding a README file (like this one!) as well is not necessary, but Etter recommends adding documentation alongside the source code in the repository.  

Your repository should look something like this:
![repo w resume only](https://i.imgur.com/gszuyhQ.png)

Congrats! You can now see your resume on GitHub Pages at the link **your_username_here.github.io**.
![plain resume](https://i.imgur.com/XxjVa53.png)

However, it's pretty boring to look at. Right now it's just plain Markdown that has been translated into HTML. In our next step, we can add some style with a Jekyll theme.


### Part 2: Generating a Static Site with Jekyll
a. Navigate to Settings, then the Pages section.

* The link to your static site is also listed at the top of this section  

b. Go to 'Choose a Theme'.

![settings](https://i.imgur.com/bgvrOKV.gif)

c. You can choose between ten different default Jekyll themes. 
* The one used in this example is called Slate.

That's it! You how have your Markdown resume hosted on GitHub Pages as a static site with a snazzy Jekyll theme. 

![jekyll resume](https://i.imgur.com/w2jPEuG.png)

Happy job hunting!


## Authors and Acknowledgments
**Written by:** Asia Miyai  
**Edited by:** Humayra Anjum Rafi, Patrick Yutuc, Joe Smith, Kamarabbas Saiyed  
**Theme template:** [Slate](https://github.com/pages-themes/slate) from the GitHub repository   
**Thank you to:**  
[A Good README Template](github.com/PurpleBooth/a-good-readme-template) by Billie Thompson  
and  
[makeareadme.com](makeareadme.com) by Danny Guo
## FAQ
*Why is Markdown better than a word processor?*  
Markdown is better to use than a word processor because it is simple to convert to HTML. As discussed by Etter in his book, Markdown is also a lot easier to learn, write, and read than other markup languages! It is also very widely used, which means it is compatible with many platforms. This makes it your best choice for any formatted text that will be published online. Be aware that there are a few different flavours of Markdown however, so be sure to check your syntax when switching between them.

*Why is my resume not showing up?*  
There are a few possible reasons why your resume is not showing up:
* You need to wait for a few minutes for GitHub Pages to update before refreshing the link again
* Your resume file is not titled index.md
* If it is showing up for you, but not showing up for other people, your GitHub account still needs to be made public
