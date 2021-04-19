# wd_s <!-- omit in toc -->

[![buddy pipeline](https://app.buddy.works/webdevstudios/wd-s/pipelines/pipeline/154066/badge.svg?token=2471ae60766a1e9a657f772e493188dde748aa18c236d0b1c325e80be13a2ac6 "buddy pipeline")](https://app.buddy.works/webdevstudios/wd-s/pipelines/pipeline/154066)

A starter theme from WebDevStudios. <https://wdunderscores.com>

[![WebDevStudios. Your Success is Our Mission.](https://webdevstudios.com/wp-content/uploads/2018/04/wds-github-banner.png)](https://webdevstudios.com/contact/)

## Table of Contents <!-- omit in toc -->

- [Introduction](#introduction)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Quick Start](#quick-start)
    - [Advanced](#advanced)
- [Installation](#installation)
    - [Development](#development)
- [Contributing and Support](#contributing-and-support)

## Introduction

Hi. I'm a starter theme called `wd_s`, or `wdunderscores`. I'm a theme meant for hacking so don't use me as a Parent Theme. Instead, try turning me into the next, most awesome, WordPress theme out there. That's what I'm here for!

I feature some of the web's most proven technologies like: [Tailwind](https://www.tailwindcss.com), [npm](https://www.npmjs.com/), [webpack](https://webpack.js.org/), [Sass](http://sass-lang.com/), and [PostCSS](https://github.com/postcss/postcss). To help you write clean code (that meets [WordPress standards](https://make.wordpress.org/core/handbook/best-practices/coding-standards/)), we tap into [@wordpress/scripts](https://developer.wordpress.org/block-editor/packages/packages-scripts/) for linting CSS and JavaScript. Did I mention that I'm also accessible? Yup. I pass both WCAG 2.1AA and Section 508 standards out of the box.

I also support [Selective Refresh](https://make.wordpress.org/core/2016/03/22/implementing-selective-refresh-support-for-widgets/) and [Live Preview](https://codex.wordpress.org/Theme_Customization_API#Part_3:_Configure_Live_Preview_.28Optional.29) in the Theme Customizer.

Not to mention, I use [Browsersync](https://www.browsersync.io/) so you can watch your project update in real-time while you work.

Looking to use some of our custom Gutenberg blocks? It's easy! Add the [WDS Blocks](https://github.com/WebDevStudios/wds-blocks) plugin for a quick starter including our Accordion and Carousel bloocks.

Looking to use some of our Advanced Custom Fields Gutenberg Blocks? It's also easy! Add the [WDS ACF Blocks](https://github.com/WebDevStudios/wds-acf-blocks) plugin for a whole set of blocks built with ACF including: Accordion, Carousel, Call To Action, Fifty/Fifty, Hero, Recent Posts, and Related Posts.

## Getting Started

### Prerequisites

Because I compile and bundle assets via NPM scripts, basic knowledge of the command line and the following dependencies are required:

- [Node](https://nodejs.org) (v14+)
- [Composer](https://getcomposer.org/)

### Quick Start

If you want to keep it simple, head over to [https://wdunderscores.com](https://wdunderscores.com) and generate your `wd_s` based theme from there. You just input the name of the theme you want to create, click the "Generate" button, and you get your ready-to-awesomize starter theme.

### Advanced

If you want to set me up manually:

1. [Download](https://github.com/WebDevStudios/wd_s/archive/main.zip) and extract the zip into your `wp-content/themes` directory and rename `wd_s-main` to fit your needs.

2. Find & Replace

You'll need to change all instances of the names: `_s`.

- Search for: `'_s'` and replace with: `'project-name'` (inside single quotations) to capture the text domain
- Search for: `_s_` and replace with: `project-name_` to capture all the function names
- Search for: `Text Domain: _s` and replace with: `Text Domain: project-name` in style.css
- Search for (and include the leading space): ` _s` and replace with: ` Project Name` (with a space before it) to capture DocBlocks
- Search for: `_s-` and replace with: `project-name-` to capture prefixed handles
- Search for `_s.pot` and replace with: `project-name.pot` to capture translation files
- Edit the theme information in the header of style.scss to meet your needs

## Installation

From the command line, change directories to your new theme directory:

```bash
cd /wp-content/themes/your-theme
```

Install theme dependencies and trigger an initial build.

>Note: You will need to have both Composer and WP-CLI installed first.

```bash
npm i --legacy-peer-deps
```

### Development

From the command line, type any of the following to perform an action:

Command | Action
:- | :-
`npm run watch` | Builds assets and starts Live Reload and Browsersync servers
`npm run start` | Builds assets and starts Live Reload server
`npm run build` | Builds production-ready assets for a deployment
`npm run lint` | Check all CSS, JS, MD, and PHP files for errors
`npm run format` | Fix all CSS, JS, and PHP formatting errors automatically

## Contributing and Support

Your contributions and [support tickets](https://github.com/WebDevStudios/wd_s/issues) are welcome. Please see our [contributing guidelines](https://github.com/WebDevStudios/wd_s/blob/main/CONTRIBUTING.md) before submitting a pull request.

wd_s is free software, and is released under the terms of the GNU General Public License version 2 or any later version. See [LICENSE.md](https://github.com/WebDevStudios/wd_s/blob/main/LICENSE.md) for complete license.
