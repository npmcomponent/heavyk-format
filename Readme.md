*This repository is a mirror of the [component](http://component.io) module [heavyk/format](http://github.com/heavyk/format). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/heavyk-format`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
format
======

printf, sprintf, and vsprintf for JavaScript


Installation
============

npm install format

The code works in browsers as well, you can copy these functions into your project
or otherwise include them with your other JavaScript.

Usage
=====

    var Format = require('format')
      , printf = Format.printf
      , format = Format.format // aliased as sprintf as well

    // Print 'hello world'
    printf('%s world', 'hello')

    var what = 'life, the universe, and everything'
    format('%d is the answer to %s', 42, what)
    // => '42 is the answer to life, the universe, and everything'

Supported format specifiers: b, c, d, f, o, s, x, and X.

See `man 3 printf` or `man 1 printf` for details.


License
=======

Copyright 2010 - 2011 Sami Samhuri sami@samhuri.net

ISC (see included [LICENSE](/samsonjs/format/blob/master/LICENSE))
