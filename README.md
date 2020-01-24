# AI 2020

1. Install dev tools and git and your favorite editor (emacs/vs code for me). These are installed by default in desk18
1. Create a private repository for this course on github, it should be called ai-mavuser, so the url to the new repo is `https://github.com/gituser/ai-mavuser`
1. Clone this repository (ai-spring2020-public) and your repository (ai-mavuser) locally.  I work in the `~/projects` directory.
1. Install conda (desk18 has that installed as well)
1. Create a local envirnoment for python using python
```bash
conda create -p env pytorch torchvision -c pytorch

```
1. Copy py3hello from my wmacevoy/csci000-astudent project to your project
```bash
cp -r py3hello ../ai-spring2020-public/
```
1. To activate the virtual environment in the project directory
```bash
conda activate ./env
```
1. From there you should be able to run the hello test in the project directory
```bash
py3hello/hellotest/hellotest.py
```

