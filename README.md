pythonparser
============

An extension of Alex Clemmer's haskell Python Parser.

# INSTALLATION

Install dependencies and build.

```bash
$ install derp
$ install MissingH
$ cabal configure
$ cabal build
```

Then run a python script with the command (example name
"hello_world.py"): 
```bash
$ cat hello_word.py | ./dist/build/pyli/pyli
```

# LICENSE

Distributed under MIT, which basically means that if you should use this code for anything, you just have to keep a note saying we wrote the code. That said, God help you should you actually decide to use this code.


## MIT License

Copyright (C) [Alex Clemmer](http://nullspace.io/) ([@hausdorff](https://github.com/hausdorff))

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
