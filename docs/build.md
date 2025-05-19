
## 初始化

```bash
python3 -m venv venv
source venv/bin/activate
pip3 install sphinx recommonmark sphinx_rtd_theme myst-parser
# 如果你要支持 Markdown + PDF：

# ② 初始化项目结构
sphinx-quickstart docs


brew install --cask font-freefont
brew install fontconfig
fc-cache -f -v 
```

## 构建

```bash

make clean
latexmk -pdf -f god-theory.tex


# 构建 HTML：
cd docs
make clean html

# 构建 PDF：
make latexpdf


```
