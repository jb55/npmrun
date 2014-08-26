
# npmrun

  Small script that adds `npm bin` to your path when running applications.

  This allows you to run project-local programs directly without resorting to
  the package.json `scripts` field and `npm run`.


## Installation

  Install with [ghi](https://github.com/stephenmathieson/ghi)

    $ ghi jb55/npmrun
  
  Or with [bpkg](https://github.com/bpkg/bpkg)
    
    $ bpkg install jb55/npmrun -g

  Or with curl

    $ curl https://raw.githubusercontent.com/jb55/npmrun/master/npmrun > ~/bin/npmrun && chmod +x ~/bin/npmrun

## Example

```bash
$ npm install --save-dev component
$ npmrun component install some/component
```

## License

  The MIT License (MIT)

  Copyright (c) 2014 William Casarin

  Permission is hereby granted, free of charge, to any person obtaining a copy
  of this software and associated documentation files (the "Software"), to deal
  in the Software without restriction, including without limitation the rights
  to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
  copies of the Software, and to permit persons to whom the Software is
  furnished to do so, subject to the following conditions:

  The above copyright notice and this permission notice shall be included in
  all copies or substantial portions of the Software.

  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
  IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
  FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
  AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
  LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
  OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
  THE SOFTWARE.
