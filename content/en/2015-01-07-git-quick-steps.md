---
title: git quick steps
author: Kang
date: '2015-01-07'
slug: git-quick-steps
categories: []
tags:
  - Git
---

Quick setup

…or create a new repository on the command line

echo "# kangyu" >> README.md
  git init
  git add README.md
  git commit -m "first commit"
  git remote add origin https://github.com/rbind/kangyu.git
  git push -u origin master

…or push an existing repository from the command line

  git remote add origin https://github.com/rbind/kangyu.git
  git push -u origin master

…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

Import code