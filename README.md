# nonlinear play

A [hugo](https://gohugo.io/) theme environment for  stand-alone creative code experiments, reducing the learning curve so you can enjoy being in the zone faster.

Our goal is to integrate, test and play with:

- processing
- p5
- ml5
- PWA (so it works well on mobile browsers)

## Installation

1. [Install hugo](https://gohugo.io/getting-started/installing/)
1. Create a hugo site
1. Install `play` as a theme submodule
	1. Go to `themes/` folder
	1. Run `git submodule add https://github.com/nonlinear/play.git play`
	1. open `config.toml` and change `theme` to `"play"`

## Updating

1. go to your hugo project folder
1. go to the theme with `cd themes/play`
1. `git pull`
1. [Subscribe to our newsletter](https://tinyletter.com/nonlinear-play/) for updates

<!-- ## Troubleshoot: submodule + githubpages

Github generates flat blogs server-side, so submodule breaks because it renames folder with commit. flat blogs are meant to be client-side, so there's a way to prevent github from rebuilding it server-side:

1. force hugo to generate flat blog on `docs/` folder, instead of default `site/` 
1. add `publishDir = "docs"` on `config.toml`
1. on github settings, tell githubpages to point to `docs/` folder instead

## 

1. build hugo with `hugo`
1. push changes -->

<!-- ## Get informed

- [Subscribe to our newsletter](https://tinyletter.com/play/) for updates
- [Join our telegram group](https://t.me/joinchat/IZcW2U4HflaCQj1G) for questions, troubleshooting, etc -->