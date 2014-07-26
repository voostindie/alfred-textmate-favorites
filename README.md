# Alfred Workflow: TextMate Favorites

## Introduction

[TextMate 2](https://github.com/textmate/textmate) is my current editor for all things text. I have many projects that I work on. TextMate has a handy "Open Favorites..." menu item - *Command + Shift + O* - to easily switch projects. Unfortunately, the current alpha (9551, at the time of writing), doesn't support modifying this list of favorites, rendering this otherwise nice feature hard to use.

Enter this [Alfred](http://www.alfredapp.com) workflow.

With this workflow you can:

* Add any folder as a favorite TextMate project from Alfred's file browser.
* Open favorite projects from Alfred in TextMate.
* Remove a project from the list of favorites with Alfred.

## Prerequisites

Well, you need a Mac of course. With TextMate on it. And Alfred, including the [productivity pack](http://www.alfredapp.com/powerpack/).

## Installation

Download the [TextMate Favorites](https://github.com/voostindie/alfred-textmate-favorites/blob/master/TextMate%20Favorites.alfredworkflow?raw=true) workflow and install it by double-clicking it.

## Usage instructions

If you already have a list of favorites set up, just type `tmf` and you should see it. Just select one and press *Return*. The project will open in TextMate. Of course you can continue typing to shorten the list.

If you don't have any favorites yet, it's time to create one:

* Using the Alfred file browser, select the directory you wish to add as a favorite.
* Open the action panel (defaults to *right arrow*).
* Select the "Add to TextMate Favorites" option and press *Return*.

This is the way to add any folder as a favorite project.

To remove a favorite, first select it in the favorites list (`tmf`) and then press *Return* while holding the *Command* key.

That's it!
