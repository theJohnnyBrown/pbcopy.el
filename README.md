# pbcopy.el - OS X clipboard integration for Emacs

Enables the Emacs kill-ring to interact with the clipboard when
running Emacs from a Mac OSX terminal (without losing full kill-ring
functionality).

## installation and activation

see the [marmalade repo page](http://marmalade-repo.org/packages/pbcopy/0.1.0)

Install with `M-x package-install pbcopy`, or in your init.el, 

    (package-install 'pbcopy)
    
After installing by either method, run 

    (require 'pbcopy) 
    (turn-on-pbcopy)
    
to activate.

## Credits

- [Kyle Bolton](https://github.com/kb)
- Leo Shidai Liu, the author of xclip.el.
