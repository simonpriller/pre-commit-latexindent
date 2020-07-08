# latexindent hook for pre-commit

[latexindent](https://www.ctan.org/pkg/latexindent) package for [pre-commit](http://pre-commit.com).

## Using latexindent with pre-commit

```yaml
-   repo: git://github.com/simonpriller/pre-commit-latexindent
    rev: master
    hooks:
    -   id: latexindent
```