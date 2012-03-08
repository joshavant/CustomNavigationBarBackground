# CustomNavigationBarView
## A sample Xcode project that implements an iOS 4.x and 5.x compatible custom navigation bar background using a 1px wide, stretchable background image.

### Discussion
The background image for `UINavigationBar` is obtained via a `[UIImage imageNamed:@...]` message. The `NSString` used for this message is taken from the `const` defined at the top of the AppDelegate.

The default background image filename is `navbar_background`. To change the background image in this demo, overwrite the appropriate files with a 1px wide, stretchable background image.

Do not extract the `JANavigationBar` class and implement it for iOS 5.x. This is a version-specific workaround for iOS 4.x.

### Compatibility
* iOS 4.0+ w/ ARC
* Xcode 4.x

**Contributions, corrections, and improvements are always appreciated!**

### Created By
Josh Avant

### License
This is licensed under a MIT/Beerware License:

    Copyright (c) 2012 Josh Avant

    Permission is hereby granted, free of charge, to any person obtaining a
    copy of this software and associated documentation files (the "Software"),
    to deal in the Software without restriction, including without limitation
    the rights to use, copy, modify, merge, publish, distribute, sublicense,
    and/or sell copies of the Software, and to permit persons to whom the
    Software is furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
    FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
    DEALINGS IN THE SOFTWARE.

    If we meet some day, and you think this stuff is worth it, you can buy me a
    beer in return.