+++
title = 'Community Notepad'
+++

Welcome to my community notepad. You can publish your notes under a heading of your choice by submitting a Github PR.

## To start writing
1. Fork `https://github.com/matt-chan/blog.git`
2. Add a folder to `content/`. The folder name becomes your category
3. Write your .md file and include the following header:
```
+++ 
title= "My Page Title" 
date= YYYY-MM-DD 
tags= ["mytag"] 
draft= <true/false> 
+++
```
4. Submit a PR back to `https://github.com/matt-chan/blog.git`. I will merge and it will automatically be published via cloudflare.