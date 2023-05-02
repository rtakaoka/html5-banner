# IPG HEALTH CHALLENGE - PART 2
This is the development log for the IPG HEALTH's HTML5 BANNER test for Senior Front End Developer position.

## How does it work?
I've listed below the important steps I took to develop the HTML5, CSS and JS code, so it becomes easy to follow. For this project specifically, I decided to go as simple as possible avoiding low code (and no-code) platform like Google Web Designer or Adobe Animate, because I believe it's more important now to demonstrate coding skills itself. So I wrote every line consciously.

## Tools I used to work on this challenge
- IDE: [Visual Studio Code](https://code.visualstudio.com/)
- Code Validator: [HTML5 Validator](https://h5validator.appspot.com/dcm/asset)
- Best Practices: [IAB HTML5 Guidelines](https://www.iab.com/guidelines/html5/)
- Design Prototype: [Figma - Go to Low Fidelity Prototype](https://www.figma.com/file/bbaJC9dKvkbPtreBVwDzGr/IPG-HEALTH-HTML5-BANNER?type=design&node-id=0%3A1&t=WZMsPqKr8abaWxTU-1)

## Overview
I started the project by structuring my thoughts so I would have a step by step linear process. It tends to transform big problems into smaller pieces easier to handle.

So here are the steps:
1. Write the core idea for the banner - [Go to section](#1-write-the-core-idea-for-the-banner)
2. Create a prototype - [Go to section](#2-create-a-prototype)
3. Research the best practices - [Go to section](#3-research-the-best-practices)
4. Write the HTML, CSS and JavaScript - [Go to section](#4-write-the-html-css-and-javascript)
5. Review and test the code - [Go to section](#5-review-and-test-the-code)
6. Deploy to the host service

## 1. Write the core idea for the banner
I decided to create a banner for an hypotetical institutional ad using ideas from [IPG HEALTH's Instagram Profile](https://www.instagram.com/ipghealth/).

## 2. Create a prototype
By looking at the IG profile and the [website](https://ipghealth.com), I got some ideas based on IPG's visual identity.
- **Gradient background:** I particularly liked [this post's background](https://www.instagram.com/p/CpLGYgqrQLQ/)
- **Font and Color:** Poppins
- **Words:** I became obsessed by the word **obsessed**
- **Text Underline Animation:** For the Call to Action, I kept the same idea used on the website's footer - where the line is animated on mouse hover.

## 3. Research the best practices
Before start writing code, it's important to know the game's rules, so I did my research and made the decision to follow IAB Guidelines.

## 4. Write the HTML, CSS and JavaScript
Now it's time to code!

- I started with the basics: `DOCTYPE`, `html`, `charset` and `viewport`
- Then I added the meta tag `ad.size`, which is defined as a best practice for ads
- Connected the links for Google Fonts
- Wrote the content `title`, `texts`, `image` and `cta`
- Wrote the CSS to animate the background and the elements
- Wrote the JS to provide the `clickTag` functionality

## 5. Review and test the code
- Before sending to the *HTML5 Validator*, I wanted to make sure it was working on my local environment. So I tested the banner with a variety of query strings for the clickTag.
- After that, I zipped the files and uploaded to the [HTML5 Validator](https://h5validator.appspot.com/dcm/asset)

## 6. Deploy to the host service
- Created a [repository on GitHub](https://github.com/rtakaoka/html5-banner)
- Deployed the project on [Netlify](https://netlify.com) - [Go to the project](https://rtakaoka-html5-banner.netlify.app/)