# Give Up GitHub

This project has given up GitHub.  ([See Software Freedom Conservancy's *Give Up  GitHub* site for details](https://GiveUpGitHub.org).)

You can now find this project at [https://codeberg.org/lejun/cooklang.nanorc](https://codeberg.org/lejun/cooklang.nanorc) instead.

Any use of this project's code by GitHub Copilot, past or present, is done without our permission.  We do not consent to GitHub's use of this project's code in Copilot.

Join us; you can [give up GitHub](https://GiveUpGitHub.org) too!

![Logo of the GiveUpGitHub campaign](https://sfconservancy.org/img/GiveUpGitHub.png)

# Cooklang Nano syntax highlight file for GNU nano text editor
Quick and dirty nanorc file for [Cooklang](https://github.com/cooklang/spec) support on [GNU nano text editor](https://www.nano-editor.org/). 
## Installation
1. Copy the file 
2. Put it in the `~/.nano/` directory
3. Add it to nano included files by adding `include ~/.nano/cooklang.nanorc` to `~/.nanorc` (User specific) or `/etc/nanorc` (System wide).
## Note
Note that being a total regexp beginner, I just couldn’t make it support single elements without using brackets. Feel free to fork, pull-request, dm or pigeon post me a solution.
