---
layout: post
title:  Hello world
date: 2023-12-16
description: this is what included TikZ code could look like
tags: formatting diagrams
categories: simple-posts
tikzjax: true
---
Hello wolds

<script type="text/tikz">
\begin{tikzpicture}
    \draw[red,fill=black!60!red] (0,0) circle [radius=1.5];
    \draw[green,fill=black!60!green] (0,0) circle [x radius=1.5cm, y radius=10mm];
    \draw[blue,fill=black!60!blue] (0,0) circle [x radius=1cm, y radius=5mm, rotate=30];
\end{tikzpicture}
</script>
