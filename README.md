## candy-theme-flat ![npm](https://badge.fury.io/js/candy-theme-flat.png)

社会化论坛项目 [Candy](http://github.com/turingou/candy) 的默认主题

### Installation 安装

Candy 默认依赖 `candy-theme-flat` 项目，因此，并不需要手动安装。如果在某些情况下需要手动安装，可以在 Candy 的工作路径执行下列代码：

```
$ npm install candy-theme-flat
```

### Example 范例代码
这段代码演示如何使用 `theme` 模块在您的项目中加载 `candy-theme-flat` 并使用其中的视图模板来渲染页面，如果需要更深入的文档，建议查看 [Theme](http://github.com/turingou/theme) 模块的相关 wiki.

````javascript
var Theme = require('theme');
var themes = new Theme(__dirname);

app.get('/home?theme=candy-theme-flat', function(req, res, next){
  res.send(theme.render('candy-theme-flat/home', {...}));
});
````

### Contributing
- Fork this repo
- Clone your repo
- Install dependencies
- Checkout a feature branch
- Feel free to add your features
- Make sure your features are fully tested
- Open a pull request, and enjoy <3

### MIT license
Copyright (c) 2014 turing &lt;o.u.turing@gmail.com&gt;

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the &quot;Software&quot;), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED &quot;AS IS&quot;, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

---
![docor](https://cdn1.iconfinder.com/data/icons/windows8_icons_iconpharm/26/doctor.png)
built upon love by [docor](https://github.com/turingou/docor.git) v0.1.2