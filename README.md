# My Earliest `Emacs` Configuration

## Description
This is the configuration that I first used as a software engineering student of ALX, when I fell in love with `emacs` and learned that I could make it work the way I want it to.
This is cool enough for anyone who likes using emacs and have similar preference with me.

## What Did I Configure it to do?
This configuration makes emacs to:
- Not show its normal start up screen *remove `'(inhibit-startup-screen t)` if you don't like the setting*
- To follow betty coding style
 - Use 8 spaces when you press tab
 - Warn for trailing white spaces
 - Warn when any line is more than 80 characters long
 - Indent properly
- Create duplicate files but save them in a hidden folder elsewhere, rather than making you have `file` and `file~` in the same directory
- Customize the colors; *and more*
##### Note that every statement that begins with `;;` (two semicolons) is a comment and actually does not do any thing in the configuration.

## How to Use This
1. Navigate to your home directory by using the command `cd ~`
2. View the hidden files to see whether `.emacs` is already there *(the command to view hidden files is `ls -a`)*
3. If it is there, copy the content of [emacs_config](./emacs_config) and make sure that no particular thing appears more than once. If `.emacs` is not there already, create it;
   - Simply enter `emacs .emacs` to create it
   - Paste these configurations inside it
   - Save and exit; check to see whether it worked