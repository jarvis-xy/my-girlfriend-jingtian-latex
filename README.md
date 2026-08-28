# 我的女友景甜

这是一个 5 x 8 英寸的 XeLaTeX 排版工程。

## 编译

需要 XeLaTeX 和标准 TeX Live 发行版：

```bash
mkdir -p build
xelatex -interaction=nonstopmode -halt-on-error -output-directory=build main.tex
xelatex -interaction=nonstopmode -halt-on-error -output-directory=build main.tex
```

## 第二篇

第二篇《回信》沿用同样的 5 x 8 英寸版式，源文件为 `second.tex`，正文为 `second.md`，机械转换后的段落文件为 `second-body.tex`。

使用 XeLaTeX 编译：

```bash
xelatex -interaction=nonstopmode -halt-on-error second.tex
xelatex -interaction=nonstopmode -halt-on-error second.tex
```

也可以使用开源的 Tectonic：

```bash
tectonic second.tex
```
