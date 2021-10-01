---
marp: true
title: Cardano Pool Guide
description: 建置 Cardano Stake Pool 正體中文手冊
theme: uncover
paginate: true
_paginate: false
---

![bg](./assets/gradient.jpg)

# <!--fit--> Cardano Pool Guide

建置 Cardano Stake Pool 正體中文手冊

https://oneleo.github.io/Cardano-Pool-Guide/

<style scoped>a { color: #eee; }</style>

<!-- This is presenter note. You can write down notes through HTML comment. -->

---

[![Marp bg 60%](./assets/CardanoTW.jpg)](https://www.facebook.com/groups/ada.tw)

---

![bg](#123)
![](#fff)
![bg right 90%](./assets/subdomain.png)

## **前置作業**

1. 申請 [FreeDNS](https://freedns.afraid.org/) 免費子網域，這邊以 114.34.34.114 指到 ada.now.im 為例

2. 安裝 2 臺 RAM 至少有 12GB 的 Ubuntu LTS 主機

---

![bg](#123)
![](#fff)

## 更新 Ubuntu 及安裝相關套件

- sudo apt-get update && sudo apt-get -y dist-upgrade && sudo apt-get -y autoremove \
- && sudo apt-get -y install ssh ufw nano vim net-tools curl wget jq libpam-google-authenticator fail2ban \
- && sudo systemctl enable ssh && sudo systemctl enable fail2ban



---

![bg](#123)
![](#fff)

![bg right 60%](./assets/subdomain.png)

##### <!--fit--> [Marp CLI](https://github.com/marp-team/marp-cli) + [GitHub Pages](https://github.com/pages) | [Netlify](https://www.netlify.com/) | [Vercel](https://vercel.com/)

##### <!--fit--> 👉 The easiest way to host<br />your Marp deck on the web

---

![bg right 60%](https://icongr.am/octicons/mark-github.svg)

## **[GitHub Pages](https://github.com/pages)**

#### Ready to write & host your deck!

[![Use this as template h:1.5em](https://img.shields.io/badge/-Use%20this%20as%20template-brightgreen?style=for-the-badge&logo=github)](https://github.com/yhatt/marp-cli-example/generate)

---

![bg right 60%](https://icongr.am/simple/netlify.svg?colored)

## **[Netlify](https://www.netlify.com/)**

#### Ready to write & host your deck!

[![Deploy to Netlify h:1.5em](./assets/netlify-deploy-button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/yhatt/marp-cli-example)

---

![bg right 60%](https://icongr.am/simple/zeit.svg)

## **[Vercel](https://vercel.com/)**

#### Ready to write & host your deck!

[![Deploy to Vercel h:1.5em](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/yhatt/marp-cli-example)

---

### <!--fit--> :ok_hand:

---

![bg 40% opacity blur](https://avatars1.githubusercontent.com/u/3993388?v=4)

### Created by Yuki Hattori ([@yhatt](https://github.com/yhatt))

https://github.com/yhatt/marp-cli-example
