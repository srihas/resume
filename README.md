# Hugo Orbit Theme

This is a Hugo port of [Orbit](//github.com/xriley/Orbit-Theme) - great looking resume/CV template designed for developers by Xiaoying Riley.

## Screenshot

![Orbit screenshot](https://raw.githubusercontent.com/aerohub/hugo-orbit-theme/master/images/screenshot.png)


## Demo

You can see it in action on [Hugo Themes site](http://themes.gohugo.io/theme/hugo-orbit-theme/).

## Contents

- [Installation](#installation)
- [Getting started](#getting-started)
    - [Configuring](#configuring)
    - [Test your site](#test-your-site)
	- [Build your site](#build-your-site)


## Installation

Install hugo - read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.


## Getting started

After installing hugo successfully, it requires just a few more steps to get your resume running.

### Configuring

Open `config.toml` and fill it with your data. All the page content may be configured through one file.
Update profile.png in `themes/hugo-orbit-theme/exampleSite/static/assets/images/` directory.

### Test your site

In order to see your site in action, run Hugo's built-in local server. 

    $ hugo server -w

Now enter `localhost:1313/resume` in the address bar of your browser.

### Build your site

Just run

	$ hugo

You'll find your resume files in `public` folder in the root of Hugo project.
