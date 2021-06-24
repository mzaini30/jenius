---
title: Cara Menggunakan Git
date: 2021-06-24
desc: Ini adalah cara menggunakan Git dengan CLI
label: git
---

## Init

```bash
git init
```

## Menghubungkan Git di Local dengan Github

```bash
git add remote add origin https://username:password@github.com/username/repo
```

## Upload ke Github

```bash
git add -A && git commit -m "pesan commitnya" && git push origin master
```

## Cek Perubahan

```bash
git status
```

## Update dari Github

```bash
git pull origin master
```

## Setting Branch Utama

```bash
git push -u origin master
```
