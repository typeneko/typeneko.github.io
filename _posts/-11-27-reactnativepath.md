---
layout: post
title: React Native 學習歷程紀錄
date: 2021-12-02
---

## Udemy Course

先找了兩個最大的課程，但發現他們都是用 expo，之前爬文就覺得一開始還是直接碰 native cli 比較好，所以就放棄退回點數，後來買了 Fadi Nouh 的 React Native: Learn By Doing [2021]（感謝黑色星期五課程都兩百多而已），課程短短的，看到中間大概了解就不想繼續看了，因為會發現有點像只是在拼 CSS 的感覺，但有大概瀏覽一下有哪些東西可以運用（課程內都用 react native 內建的 components）。  
總之大概要先學會環境、Navigation 基本、就有辦法用 react 做出一個很純粹的 App 了。

## Youtube

到處看影片想要多找到一些學習方向的關鍵字，然後發現有 NativeBase（給我類似 chakra-ui 的感覺，覺得神便利）、Reanimated、Moti、RevenueCat等等可以用，都需要實作再去學。不知道有沒有需要特別運用 Redux，這部分有想要繼續了解。

## Database

這個真的很難爬文，比較了一下，目前我要做的比較偏 offline 端，所以選 Realm（好像被 mongodb 買了，所以雲端同步也有方案，等以後實做看看）。如果要做比較即時的服務，應該會選 Firebase。  
之前用 couchdb 做的經驗，覺得自己架太麻煩了，現在 backend 就算要花錢，也想要能越簡單越好。
關於更新會不會動到 local 資料，爬文都說不會，等實做測試，應該會需要對 db version 跟 migration 有更多了解。  
太久沒用 jekyll，調整一下圖片顯示方式  
![test](/assets/pictures/test/1.jpg)
