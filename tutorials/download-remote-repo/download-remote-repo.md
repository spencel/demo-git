How to Download a Repo
=

Downloading a remote repo is called cloning, i.e., you are making a copy of the repo. This tutorial will use GitHub as an example.

1. Find the URL of your remote repo. On GitHub, you can navigate to your repo and then click on *Clone or download* and copy the URL; or, you can find the URL using the template below:

```
https://github.com/your-username/your-git-repo-name.git
```
For example:
```
https://github.com/spencel/demo-git.git
```

2. In a CLI, navigate to the directory where you would like to download the remote repo to and execute the command below, which will copy the repo of this tutorial onto your machine.

```
git clone your-git-url.git
```
For example, to download this repo:
```
git clone https://github.com/spencel/demo-git.git
```
You may notice a .git directory 

3. To download the most recent version of a remote repo, which is common if you are using a utility or a module for your own project, then use the command below with the actual URL of the repo.

```
git pull git-repo-url.git
```

Next: Uploading changes to your own remote repo (coming soon...)

Resources:
- [guides.github.com](https://guides.github.com/)