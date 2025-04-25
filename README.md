<!-- Please update value in the {}  -->

<h1 align="center">Bento Box Layout | devChallenges</h1>

<div align="center">
   Solution for a challenge <a href="https://devchallenges.io/challenge/bento-box-layout-challenge" target="_blank">Bento Box Layout Feature Section</a> from <a href="http://devchallenges.io" target="_blank">devChallenges.io</a>.
</div>

<div align="center">
  <h3>
    <a href="https://mlvoorhis.github.io/bentobox-feature-section-master/">
      Demo
    </a>
    <span> | </span>
    <a href="https://github.com/mlvoorhis/bentobox-feature-section-master">
      Solution
    </a>
    <span> | </span>
    <a href="https://devchallenges.io/challenge/bento-box-layout-challenge">
      Challenge
    </a>
  </h3>
</div>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Overview](#overview)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Built with](#built-with)
- [Features](#features)
- [Contact](#contact)

<!-- OVERVIEW -->

## Overview

![screenshot](https://csyxkpbavpcrhwqhcpyy.supabase.co/storage/v1/object/public/challenges/68/challenge-68-thumbnail)

This project provided valuable hands-on experience with CSS Grid, especially when working with nested grids and adjusting layouts based on different configurations like 75%/25% or 25%/75%. I initially struggled with layout techniques, but learned that Flexbox's flex-basis could’ve simplified things, sparing me the complexity of nested grids. I also discovered the power of using padding and gap for consistent spacing, avoiding margin issues like doubling up.

### What I learned
<b>Nested Grids</b>:
This project gave me a lot of hands-on experience with nested grids,  using <code>grid-template-areas</code>, <code>grid-column</code>, <code>grid-template-columns</code>, and <code>grid-template-rows</code>. I learned how tricky it can be to manage the layout, especially when flipping the order of box items. Managing these nested grids for different box configurations (like switching between 75%/25% and 25%/75% columns) added unnecessary complexity to the project, making it harder to maintain.

<b>Flexbox</b>:
While I initially tried using <code>display: flex</code> and <code>flex-direction: column-reverse | row-reverse</code>, I abandoned my efforts, because I thought I wouldn't be able to lay them out unevenly (e.g. 60/40). I was wrong! <code>flex-basis</code> would've given be the effect I wanted without the headache. At least I got some valuable experience with some tricky nested grids.

<b>Padding & Gap for Consistent Spacing</b>:
When I used <code>margin</code> for the individual box spacing, I was having issues with the margins doubling up. I realized a simpler approach was to add <code>padding</code> for the outside lines and <code>gap</code> for the inside lines. 

### Useful resources
- [Free Code Camp](https//www.FreeCodeCamp.org) - My foundation in HTML/CSS
- [W3Schools](https://www.w3schools.com/cssref/pr_grid.php) - Where I spent a bunch of time troubleshooting grid layouts.

### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

## Features
This application/site was created as a submission to a [DevChallenges](https://devchallenges.io/challenges-dashboard) challenge.

## Contact

- GitHub [@mlvoorhis](https://github.com/mlvoorhis)