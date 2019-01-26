# Travel Site

[![Known Vulnerabilities](https://snyk.io/test/github/kabuk1/travel-site/badge.svg?targetFile=package.json)](https://snyk.io/test/github/kabuk1/travel-site?targetFile=package.json)

A hands-on project from [Udemy: Git a Web Developer Job: Mastering The Modern Workflow by Brad Schiff](https://www.udemy.com/git-a-web-developer-job-mastering-the-modern-workflow/).

## Live Demo

You can see the completed website in action [here](https://kabuk1.github.io/travel-site/).

## Features

* Mobile-first performance and responive web design:

  * Lazy-loading images, icon sprites, responsive images
  
  * Icon sprites for faster page load time

* Support for legacy browsers:

  * Picturefill to ensure responsive images

  * Test browser support for SVGs and flexbox with gulp-modernizr

  * Convert SVGs to PNGs with gulp-svg2png

* Reveal page contents on scroll

* Smooth page scroll to an anchor on the same page

## Getting Started

### Clone or download this repository

```sh
git clone https://github.com/kabuk1/travel-site.git
```

### Prerequisites

```sh
Node.js install
```

```sh
NPM install
```

## Built with

### Library

* jquery

### Build Tools

* Gulp
* PostCSS
* Babel
* Webpack
* normalize.css
* lazysizes
* waypoints

### Testing

* browsersync

## Deployment

Bundle all files together in git bash using gulp:

```
gulp build
```
To preview your build project using gulp:

```
gulp previewdist
```

## Acknowledgments

* Thanks to [Brad Schiff](https://github.com/LearnWebCode) for a fantastic course on workflow. 

