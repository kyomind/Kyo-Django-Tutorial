![Kyo's Django Tutorial](https://i.imgur.com/D4mTT4l.png)

[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-blue?labelColor=444&logo=pre-commit)](https://github.com/pre-commit/pre-commit)
![](https://img.shields.io/codecov/c/github/kyomind/kyo-django-tutorial?labelColor=444&logo=codecov&color=blue)
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)

這個倉庫是我的部落格——[Code and Me](https://blog.kyomind.tw/)——技術類教學文章的**範例程式碼**。以 [Django Tutorial](https://blog.kyomind.tw/tags/Django-Tutorial/) 系列為主軸，所以它是一個 Django 專案，但也包括本站其它技術文章內容實作。請參考下方的相關文章列表。

## 分支說明

每一個分支格式如下：

```
01-django-models
```

其中 `01` 代表**文章發表的順序**編號，`django-models` 代表文章網址 slug，分支內容為該文章所新增的程式碼。

分支主要作為歷史記錄之用，但有些特殊情況的程式碼，可能也需要使用特定的分支保留。一般言而，分支會在文章發佈後，合併到 `main` 。

## 相關文章列表

| 分支                       | 文章標題                                                         |
|--------------------------|--------------------------------------------------------------|
| 01-django-models         | [Django ORM：一對一、一對多外鍵教學（上）前言與關聯設定](https://blog.kyomind.tw/django-models/) |
| 02-ruff                  | [Python 開發：Ruff Linter、Formatter 介紹 + 設定教學](https://blog.kyomind.tw/ruff/) |
| 03-reverse-relationships | [Django ORM：一對一、一對多外鍵教學（中）反向關聯](https://blog.kyomind.tw/reverse-relationships/) |
