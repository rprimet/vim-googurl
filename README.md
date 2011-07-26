vim-googurl
===========

## Description

A vim plugin to easily create [Markdown](http://daringfireball.net/projects/markdown/) links from a [Google](http://www.google.com/) query. I wrote this script because I used to toggle back and forth between vim and my web browser when inserting links into text.

## Install

Just drop the file `googurl.vim` into your `~/.vim/plugin` directory.
vim-googurl needs ruby support compiled in vim, and the following gems:

- json

## Use

The plugin will define a `FindUrls` command. Put your cursor over a word, call `:FindUrls` and you will be offered a set of choices drawn from Google.

## License

    Copyright (c) 2011 Roma1n
   
    Permission is hereby granted, free of charge, to any 
    person obtaining a copy of this software and associated documentation 
    files (the "Software"), to deal in the Software without restriction, 
    including without limitation the rights to use, copy, modify, merge,
    publish, distribute, sublicense, and/or sell copies of the Software, 
    and to permit persons to whom the Software is furnished to do so, 
    subject to the following conditions:
    
    The above copyright notice and this permission notice shall be 
    included in all copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, 
    EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
    OF MERCHANTABILITY, SANITY, FITNESS FOR A PARTICULAR PURPOSE 
    AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR 
    COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
    WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
    ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR 
    THE USE OR OTHER DEALINGS IN THE SOFTWARE.

