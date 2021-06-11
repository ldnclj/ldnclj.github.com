# London Clojurians Website

This repository contains the build of a ClojureScript & Reagent Single Page Application, created from the [ldnclj/landing-page](https://github.com/ldnclj/landing-page) project.


## Deploy new versions

Create a build of the ClojureScript single page app using the instructions in the [ldnclj/landing-page](https://github.com/ldnclj/landing-page) project.

Copy the updated contents of the `/docs` directory of that project to the root of this project

```shell
cp -vir ../org.londonclojurians.landing-page/docs/* js/main.js
```

Commit the changes and push to GitHub.  Within a few minutes (usually less) the new version of the ClojureScript single page app will be available at https://londonclojurians.org/
