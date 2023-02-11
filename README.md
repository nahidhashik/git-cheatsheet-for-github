<!--git-cheatsheet-for-github  -->
![9](https://user-images.githubusercontent.com/37225357/217484795-6124aa97-5b23-4095-ad95-c29be3ede4c8.png)


#   WHY Git?
[Git](https://github.com/) is a version control system. Its original purpose was to help groups of developers work collaboratively on big software projects. Git manages the evolution of a set of files – called a repository – in a sane, highly structured way.


# WHY Github?
Understanding [GitHub](https://github.com/) isn't complicated, I think! But at first, we have to understand Git. Well, Git is an open-source version control system that was started by Linus Torvalds—the same person who created Linux.

Version control system means for example when developers create something such as an app, they frequently change the code and releasing new versions up to and after the first official (non-beta) release, this system always keeps these revisions straight, storing the modifications in a central repository.

By this developers can easily collaborate, can download the beta version also can make changes to the code, and tries to upload the newest versions, same as unofficial developers can still download the files and use them.


# GitHub Definition
Coders can share ideas and methods and make awesome software and GitHub brings them together as a team and coding experts onto one collaborative platform. Sounds difficult to hear? Let me explain it in further detail.

GitHub is a code hosting platform for Coders and Non-coders to work together on projects. Anybody can take advantage of Git by GitHub. Without GitHub, using Git generally requires a bit more technical savvy and use of the command line.


# Benefits of GitHub?
Why! GitHub? There are several reasons for that.

It enables slick and easy collaboration with version control.
This allows you to work on code with anyone from anywhere.
If you plan on getting a job, you’ll look really good if you already know your way around GitHub
It allows multiple developers to work on a single project at the same time.
It reduces the risk of duplicative or conflicting work and can help decrease production time.
With GitHub, developers can build code, track changes, and innovate solutions to problems that might arise during the site development process simultaneously.
 Non-developers can also use it to create, edit, and update website content, which Carpenter demonstrates in her tutorial.

 # INSTALLATION
This site was built using For [windows download](https://gitforwindows.org/) Git bash from here

[Watch This Tutorial](https://www.youtube.com/watch?v=QkgiXDvpMGc)


# Create Github Account
[Watch This Tutorial](https://www.youtube.com/watch?v=unc4D5TvZJE)

# Create Repository in Your Github
[Watch This Tutorial](https://www.youtube.com/watch?v=2rPqWnGW_ns&t=7s)

# Using Github from Windows git
[Watch This Tutorial](https://www.youtube.com/watch?v=pYYm9Qr0y_U&t=903s)

# How to Host a Website on GitHub Pages for Free
[Watch This Tutorial](https://www.youtube.com/watch?v=xKTY3wfxhtc&t=2s)

# Git bash Commands for Github

# Basic

**git --version**
You can check your current version of Git by running the git --version command in a terminal (Linux, macOS) or command prompt (Windows)

```
user@localhost:~$ git --version
```

![version](https://user-images.githubusercontent.com/37225357/217600317-f33ad1c2-bcfa-4717-b55e-f888e7a51594.PNG)

**git clone**

```
user@localhost:~$ git clone
```

![clone](https://user-images.githubusercontent.com/37225357/217614357-0e4b15fb-123c-4ec0-a834-56b04271d97a.PNG)


**ls**

```
user@localhost:~$ ls
```
![ls](https://user-images.githubusercontent.com/37225357/217614737-83596dc8-9a81-4812-8e56-c8a911557895.PNG)


**cd DirectoryName**

```
user@localhost:~$ cd new_dir
```
![mkdir](https://user-images.githubusercontent.com/37225357/217619785-07d08aa8-0441-4b87-9ed7-9ecfb0980b16.PNG)



**cd ..**

```
user@localhost:~$ cd ..
```
![cdplus](https://user-images.githubusercontent.com/37225357/217621041-f4fb8dd1-9ba0-43b5-a2e6-21b6a64254cd.PNG)
<!-- **mkdir DirectoryName** -->

<!-- **touch** -->

**git add .**

```
user@localhost:~$ git add .
```
![add](https://user-images.githubusercontent.com/37225357/217620283-8749e290-dce6-4503-9f92-cebab1b18b0e.PNG)

**git commit -m ""**

```
user@localhost:~$ git commit -m "your message"
```
![commit](https://user-images.githubusercontent.com/37225357/217621928-1ec7bd82-03b3-4edd-8ec6-4c9a2745cc5c.PNG)

**git push origin BranchName**

```
user@localhost:~$ git push origin main
```
![pushorigin](https://user-images.githubusercontent.com/37225357/217622125-d43fef32-0c5a-41f9-9eb0-38bf4c84b500.PNG)


# Status Check

**git status**

```
user@localhost:~$ git status
```
![status](https://user-images.githubusercontent.com/37225357/217622648-9b274a44-ff57-4638-acf4-e957c8214b4f.PNG)

**git log**

```
user@localhost:~$ git log
```
![log](https://user-images.githubusercontent.com/37225357/217622662-4f53e44c-e4c9-46e5-9cf2-d711b2eda41a.PNG)


# Create file

**touch FileName**

```
user@localhost:~$ touch NewFile
```

![touch](https://user-images.githubusercontent.com/37225357/217620506-0f860c76-8ad3-4080-864a-ed56e85b538b.PNG)

# Delete file

**rm FileName**

```
user@localhost:~$ rm NewFile
```
![rm](https://user-images.githubusercontent.com/37225357/217623668-9501c37a-65b3-4ae4-9de6-8b4e07508000.PNG)

# Create Directory

**mkdir DirectoryName**

```
user@localhost:~$ mkdir new_dir
```
![mkdir](https://user-images.githubusercontent.com/37225357/217624212-6c7b9ef8-7500-49df-80be-2fb407b48fd6.PNG)


# Delete directory

**rmdir DirectoryName**

```
user@localhost:~$ rm new_dir
```
![rmdir](https://user-images.githubusercontent.com/37225357/217624932-3ebb6577-135e-4369-8eca-d0e09d88c362.PNG)


# Branch Create

**git branch**

```
user@localhost:~$ git branch
```
![branch](https://user-images.githubusercontent.com/37225357/217625557-e40e35ce-8069-4c6e-bae2-6a9ee7a4d672.PNG)


**git branch NewBranchName**

```
user@localhost:~$ git branch seond_branch
```
![newbranch](https://user-images.githubusercontent.com/37225357/217627198-a4dc9daa-85bf-4980-bc4a-5df5234717ee.PNG)


**git checkout BranchName**

```
user@localhost:~$ git checkout second_branch
```
![checkout](https://user-images.githubusercontent.com/37225357/217627721-a239252c-301a-4fb8-9b19-266aefad88b3.PNG)



# Pull Request

**git pull origin BranchName**

```
user@localhost:~$ git pull origin second_branch
```
![pull](https://user-images.githubusercontent.com/37225357/217631631-44fe8cb9-5758-4dd4-be11-b8ba3fe8e5ca.PNG)


# Merge Request

**git merge BranchName**

```
user@localhost:~$ git merge second_branch
```
![merge](https://user-images.githubusercontent.com/37225357/217632173-4eba79bb-6d5f-47c9-b8f7-104492ce18bf.PNG)


# Note
Every changes you neeed to three commands

**git add .**

```
user@localhost:~$ git add .
```
![add](https://user-images.githubusercontent.com/37225357/217620283-8749e290-dce6-4503-9f92-cebab1b18b0e.PNG)


**git commmit -m " "**

```
user@localhost:~$ git commit -m "your message"
```
![commit](https://user-images.githubusercontent.com/37225357/217621928-1ec7bd82-03b3-4edd-8ec6-4c9a2745cc5c.PNG)


**git push origin BranchName**

```
user@localhost:~$ git push origin main
```
![pushorigin](https://user-images.githubusercontent.com/37225357/217622125-d43fef32-0c5a-41f9-9eb0-38bf4c84b500.PNG)


# License

[MIT-LICENSE.md](https://github.com/nahidhashik/git-cheatsheet-for-github/blob/main/LICENSE.md)



# Conclusion
Fork, pull request, and merge – are three features that make GitHub so powerful. If you wanted to contribute to an open-source project you had to manually download the project’s source code, make your changes locally, create a list of changes called a “patch” and then e-mail the patch to the project’s maintainer. The maintainer would then have to evaluate this patch, possibly sent by a total stranger, and decide whether to merge the changes.


