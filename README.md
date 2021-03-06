# gitlogviz

Use graphviz to visualize your git commit log!

First, go to [graphviz.org](http://graphviz.org/) and install the software. It's free!

Second, run this script from the top level of a git repository, like so:

    gitlogviz.rb | dot -Tpdf -o git-log.pdf

Third, open `git-log.pdf` in a PDF viewer to impress your friends and confound your enemies!

## Sample Output

![Sample Image](https://github.com/gismo141/gitlogviz/raw/master/sample.png)

## License

Copyright (c) 2012 Benjamin Ragheb

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the 'Software'), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
