vim-byline
==========

Vim-Byline is a simple statusline implementation. It has separate colors for the file extension and file path. It changes colors on inactive windows. And it shows the read-only and unsaved symbols in red.


# configuration
===============

There is no configuration at this time. Please send me a message if you would like any particular configuration settings.


You can override the colors. The following colors are used.

```
    hi StatusLineFile guibg=#9bfb9b guifg=#000000
    hi StatusLineFileInactive guibg=#7bbb9b guifg=#504000
    hi StatusLineExtensionActive guibg=#ffff00 guifg=#555555
    hi StatusLineExtensionInactive guibg=#698a8a guifg=#555555
    hi StatusLineActive guibg=#c9fB99
    hi StatusLineInactive guibg=#888888
    hi User1 term=inverse,bold gui=inverse,bold guifg=#ff0000
    hi User2 guibg=#bbcbfb
```
