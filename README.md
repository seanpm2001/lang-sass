<!-- NOTE: README.md is generated from src/README.md -->

# @codemirror/lang-sass [![NPM version](https://img.shields.io/npm/v/@codemirror/lang-sass.svg)](https://www.npmjs.org/package/@codemirror/lang-sass)

[ [**WEBSITE**](https://codemirror.net/) | [**ISSUES**](https://github.com/codemirror/dev/issues) | [**FORUM**](https://discuss.codemirror.net/c/next/) | [**CHANGELOG**](https://github.com/codemirror/lang-sass/blob/main/CHANGELOG.md) ]

This package implements Sass/SCSS language support for the
[CodeMirror](https://codemirror.net/) code editor.

The [project page](https://codemirror.net/) has more information, a
number of [examples](https://codemirror.net/examples/) and the
[documentation](https://codemirror.net/docs/).

This code is released under an
[MIT license](https://github.com/codemirror/lang-css/tree/main/LICENSE).

We aim to be an inclusive, welcoming community. To make that explicit,
we have a [code of
conduct](http://contributor-covenant.org/version/1/1/0/) that applies
to communication around the project.

## API Reference

<dl>
<dt id="user-content-sass">
  <code><strong><a href="#user-content-sass">sass</a></strong>(<a id="user-content-sass^config" href="#user-content-sass^config">config</a>&#8288;?: {indented&#8288;?: <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean">boolean</a>}) → <a href="https://codemirror.net/docs/ref#language.LanguageSupport">LanguageSupport</a></code></dt>

<dd><p>Language support for CSS.</p>
</dd>
<dt id="user-content-sasslanguage">
  <code><strong><a href="#user-content-sasslanguage">sassLanguage</a></strong>: <a href="https://codemirror.net/docs/ref#language.LRLanguage">LRLanguage</a></code></dt>

<dd><p>A language provider based on the <a href="https://github.com/lezer-parser/sass">Lezer Sass
parser</a>, extended with
highlighting and indentation information.</p>
</dd>
</dl>