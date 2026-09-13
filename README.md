# c.vim
Improved syntax plugin for C for vim that adds highlighting support for: **types**, **members access**, **constants** and more.
This plugin extends vim's default C syntax.

![screenshot](https://github.com/rayleigh-gamma/c.vim/blob/main/extra/images/screenshot.png?raw=true)

## Recommended features
To get full syntax features, add this to your `.vimrc`:
```vim
" Highlight strings inside multi-line comments.
let c_comment_strings = 1
" Fixes red background around brackets.
let c_no_bracket_error = 1
" Fixes red background around curly braces.
let c_no_curly_error = 1
" Use C syntax for headers files instead of C++ syntax.
let c_syntax_for_h = 1
" Do not highlight #if 0 as a comment.
let c_no_if0 = 1
" Highlight functions declarations/calls.
let c_functions = 1
" Highlight function pointer definitions.
let c_function_pointers = 1
```

For more information, check `:help c.vim`.

# Additional
The colorscheme in the screenshot can be found [here](https://github.com/rayleigh-gamma/caramel.vim).
