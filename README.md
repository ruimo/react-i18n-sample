---
theme: "beige"
transition: "slide"
slideNumber: false
title: "React-i18nextを利用したi18nの実践例"
---

# React-i18nextを利用したi18nの実践例

---

## 概要

![Abstract](figures/abstract.drawio.svg)

図1 概要

* 複数の画面で共通で使用するメッセージはnpm packageにして再利用できるようにする。
* 利用者側は、共通のメッセージと固有のメッセージ両方を利用できる。
* 共通のメッセージは複数用意することが可能(名前空間で使い分ける)。

---

## npm package registry

今回はGitHubを使用していますが、[Verdaccio](https://verdaccio.org)や[GitLab](https://about.gitlab.com)などnpm package registryに対応したものを適宜利用してください。
本資料ではこれらのpackage registryの設定方法については省略します。


