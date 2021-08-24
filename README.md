# [coffee-blog](https://coffee-blog-e946f9.netlify.app/)
This is the fourth project from Juan Pablo's course of [Web Development](https://www.udemy.com/course/desarrollo-web-completo-con-html5-css3-js-php-y-mysql/).

> **Note:** Recently I've started to deploy my sites on [Netlify](https://app.netlify.com/), therefore I changed the domain's link to the new one (in the HTML and the README files), but I kept the screenshots that held the old domain (there's no reason for changing it, the result would've been the same with a different link only).

> **Disclaimer:** I'm starting to learn how to use **Git/Github** correctly, therefore there'll be plenty of pull requests, commits and other stuff as tests in this repository, however, *this won't represent my way of working forever*, I'll learn more things along the way as always :D!.

## Table of contents
* [Preview](#preview)
* [What I learned](#what-i-learned)
* [Reports](#reports)
    - [Lighthouse](#lighthouse)
* [Open Graph](#open-graph)
    - [Facebook](#facebook)
    - [Twitter](#twitter)

## What I learned

> **Note:** in this project, I continued practicing with the SMACSS methodology (maybe in the next project I'll apply another architecture for building projects with SASS).

* I have a few doubts about the picture element ... I thought that when you put properties in the img tag that's inside the picture element, you didn't have to add them in the source tag (due to the img tag is rendered first for the browser, and then...once it's already charged, if it's possible, it changes the image for one available in the source tag, but...the properties in the img tag are kept). But in the part of the course where this project was, the instructor put properties like "loading" twice in picture elements (one in the source tag, and the other in the img tag), therefore I'm a little bit confused about it even though I'm almost sure that I'm right (I'll keep looking for more information until be completely sure about everything I mentioned before).

* I also tried to use more utilities in the project, thus I created classes like "no-margin", "no-padding", "txt-center", etc. (I'll keep looking for more utilities that could be useful for me in future projects).

> That'd be everything for this project :D.

> **P.D.** I've already found out more information about properties like "loading" in the picture element, and I was right (you should put the properties like "loading" or "alt" in the img tag only), for more information you can check [this article](https://web.dev/browser-level-image-lazy-loading/).

## Reports

### Lighthouse
![](readme/lighthouse.png)

## Open Graph

### Facebook

> **Note:** each page has a different card (image, title, description, etc.).

![](readme/facebook.png)

### Twitter

> **Note:** each page has a different card (image, title, description, etc.).

![](readme/twitter.png)
