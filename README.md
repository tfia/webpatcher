# Web Patcher (self-hosted fork)

Self-hosted fork of [asterisk727/webpatcher](https://github.com/asterisk727/webpatcher), based on the community-maintained RE: TWO-TORIAL Web Patcher.

**Site:** https://tfia.github.io/webpatcher/  
**CHUNITHM MATE (2.50):** https://tfia.github.io/webpatcher/chusanmate.html

## GitHub Pages setup

This repository is a static HTML/CSS/JavaScript website. No build step is needed.

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select **main** and **/(root)**, then save.
4. Allow GitHub Pages to publish the site at the URL above.

The upstream custom-domain `CNAME` file has been removed so this fork will use the default `github.io` project URL. If configuring a custom domain later, add your own domain through the Pages settings.

## Usage

Select a game/version from the home page, choose its corresponding executable or data file, apply patches, and save the modified file. **Back up the original first.** Patch offsets and expected bytes are version-specific. The site includes CHUNITHM MATE 2.50; it does not imply that patches work on other builds.

## Upstream & attribution

Source and original maintenance: [asterisk727/webpatcher](https://github.com/asterisk727/webpatcher). Refer to the original repository for contribution instructions and license. This fork is independently hosted; upstream links, branding, and resources in the pages remain credited to their creators.
