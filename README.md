nicEdit-HTML5
=============

Fork of nicEdit attempting to produce better markup and add a couple of features.

## Why
nicEdit is one of few WYSIWYG editors I have found that allow one toolbar to control several inline contentEditable elements. It's also quite small compared to many of the alternatives.

However, as it uses the browsers' built-in functionality (execCommand) it produces old-fashioned markup like ```<font size=2>```. This project tries to remedy that.
More info on original site: http://wiki.nicedit.com/w/page/527/XHTML%20Compliant%20Output

## Alternatives
I've looked at many alternatives but was not satisfied with any single one (e.g. too big/the wrong license/buggy/not the necessary features).
Here are the ones I've evaluated:

* Redactor - http://imperavi.com/redactor
* Mercury - http://jejacks0n.github.com/mercury
* Etch - http://etchjs.com
* CKEditor - http://ckeditor.com
* Aloha Editor - http://aloha-editor.org
* WYSIHTML5 - http://xing.github.com/wysihtml5
* Hallo - http://hallojs.org
* TinyMCE - http://www.tinymce.com

## Original project
The original nicEdit project can be found here: http://nicedit.com/

From that website:
> NicEdit was developed by [Brian Kirchoff](http://bkirchoff.com/) and is free to use for any purpose under the MIT license.

Features listed for original project:

* Small file size <35KB Total, <10KB Compressed!
* Only 2 files (js + icons) required for operation.
* Flexible Configuration replace textareas or divs
* Multiple editors can optionally use single controls
* Save content via AJAX or HTTP Post
* IE 5.5+ / FF 2+ / Opera 9+ / Safari 3+

## LICENSE
nicEdit comes with the following license information (see src/nicLicense.js):
```
/* NicEdit - Micro Inline WYSIWYG
 * Copyright 2007-2008 Brian Kirchoff
 *
 * NicEdit is distributed under the terms of the MIT license
 * For more information visit http://nicedit.com/
 * Do not remove this copyright message
 */
 ```
 
From website (http://nicedit.com/license.php):
> Copyright (c) 2007-2008 Brian Kirchoff (http://nicedit.com)

> Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

> The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
