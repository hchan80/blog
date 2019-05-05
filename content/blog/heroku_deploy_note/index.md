---
title: Heroku Deploymeny Cheatsheet
date: "2019-05-05"
description: "Heroku"
---

# Deployment on Heroku

The dedployment process on Heroku is simple. 

### Checklist

Ensure running the following commands returns no error messages.
```sh
$ node --version
$ npm --version
$ heroku --version
```

### Deployment

Deployment on Heroku can be done completely on terminal. 

| Purpose | Command |
| ------ | ------ |
| Login Heroku | heroku login |
| Create a new Heroku deployment project | heroku create |
| Push the "Gitted" local project to Heroku  | git push origin master|
| Update the project on Heroku | git push heroku master |

Happy Coding !