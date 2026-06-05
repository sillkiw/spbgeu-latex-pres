# SPbGEU Beamer Template

Сборка:

```bash
xelatex main.tex
```

Основной вариант - `xelatex`: он использует системный `Noto Sans` с нормальными жирными начертаниями. Для аварийной сборки через pdfTeX можно использовать:

```bash
TEXMFVAR=/tmp/texmf-var TEXMFCACHE=/tmp/texmf-cache pdflatex main.tex
```

Шаблонные макросы находятся в `spbgeu-beamer.sty`, фоновые изображения и иконки - в `assets/`.
