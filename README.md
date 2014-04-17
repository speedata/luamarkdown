# Pure Lua implementation of markdown

This is a copy from <http://www.frykholm.se/files/markdown.lua> with some changes:

* Compatible with Lua versions 5.1 and 5.2
* Different interface, markdown.lua makes no changes anymore to the global namespace:

        local md = require('markdown')
        md.markdown(txt)



License: MIT like license, see the source file for details.

