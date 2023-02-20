---
title: "Autotag Diffusion"
date: 2023-02-20T15:06:47+09:00
draft: false
tags: ["python", "stable_diffusion", "image"]
outputs: [html, json]
hero: ""
---

### イメージからタグを抽出しそのタグでイメージ生成

danbooru のタガーライブラリを利用してイメージからタグを生成し、

そのタグのイメージを StableDiffusion の img2img で生成します。

意外と良い結果になっていた記憶があります。
