1. License

The MIT License

Copyright (c) 2011 Brett Cunningham, Matt Sabourin 

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


2. Usage

./fuzz2sql.py <windows executable>

3. How it works

The fuzz2sql script will break apart a PE File (typically .exe's and .dll's) into their sections (i.e.: .data, .text, .rdata, etc.) and perform Context Triggered Piecewise Hasing (fuzzy hash). It will store the results in an sqlite database, as well as print to the screen.

PE files feed to the program will be referenced by their md5. It is suggested to build some metholodolgy to refer back to PE files by their md5.

4. Contact Us

Please use github's Issues page for tracking bugs, or irc.freenode.com #snorby (jbc22).
