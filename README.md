# reykjavik-theme

Emacs theme with a dark background and low saturated colors.

Created with [ThemeCreator](https://github.com/mswift42/themecreator).

Screenshots:
------------

Javascript and ruby:
![Screenshot ](https://github.com/mswift42/reykjavik-theme/raw/master/tc1emacsreykjavik.png)

Clojurescript:
![Screenshot ](https://github.com/mswift42/reykjavik-theme/raw/master/tc1reykjavikemacsclojure.png)

* * *

Available on Melpa.

Installation Instructions
-------------------------

add the following lines to your init.el (only if you have not done so already):

    (setq package-archives '(("gnu" . "http://elpa.gnu.org/packages/")
                             ("melpa" . "http://melpa.org/packages/")))
    (package-initialize)



This will add the gnu and melpa repos to your emacs setup.

To install the theme:

**M-x package-install** reykjavik-theme


To use the reykjavik theme when starting emacs, add this to your init.el:

    (load-theme 'reykjavik)

## Features for emacs-27 and beyond

1. `tab-line` is supported

A nice way of using it is:

```
(require 'tab-line)

(global-tab-line-mode (if (display-graphic-p) t -1))
```
