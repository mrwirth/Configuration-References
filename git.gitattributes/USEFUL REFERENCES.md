# Useful references for making .gitattributes rules

## Notes
- Only add `eol=???` when there's a reason for having a particular eol, like current or historical tooling issues.  Otherwise, user's `autocrlf` should dominate.

## Documentation
- [**.gitattributes documentation**](https://git-scm.com/docs/gitattributes): Official documentation for .gitattributes.

### Extract: The following built in patterns are available for `diff=`:
- ada suitable for source code in the Ada language.
- bash suitable for source code in the Bourne-Again SHell language. Covers a superset of POSIX shell function definitions.
- bibtex suitable for files with BibTeX coded references.
- cpp suitable for source code in the C and C++ languages.
- csharp suitable for source code in the C# language.
- css suitable for cascading style sheets.
- dts suitable for devicetree (DTS) files.
- elixir suitable for source code in the Elixir language.
- fortran suitable for source code in the Fortran language.
- fountain suitable for Fountain documents.
- golang suitable for source code in the Go language.
- html suitable for HTML/XHTML documents.
- java suitable for source code in the Java language.
- kotlin suitable for source code in the Kotlin language.
- markdown suitable for Markdown documents.
- matlab suitable for source code in the MATLAB and Octave languages.
- objc suitable for source code in the Objective-C language.
- pascal suitable for source code in the Pascal/Delphi language.
- perl suitable for source code in the Perl language.
- php suitable for source code in the PHP language.
- python suitable for source code in the Python language.
- ruby suitable for source code in the Ruby language.
- rust suitable for source code in the Rust language.
- scheme suitable for source code in most Lisp dialects, including Scheme, Emacs Lisp, Common Lisp, and Clojure.
- tex suitable for source code for LaTeX documents.

## Examples
- [**gitattributes/gitattributes*](https://github.com/gitattributes/gitattributes): A git repo with several useful templates.
