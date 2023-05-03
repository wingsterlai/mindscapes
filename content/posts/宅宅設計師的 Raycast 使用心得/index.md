---
title: "宅宅設計師的 Raycast 使用心得"
description: 提高生產力及工作效率的 Mac 軟體
date: 2023-04-29T14:41:42+08:00
cover:
    image: 
    alt: ''
    caption: ''
categories: ["生產力"]
tags: ["工具", "Designer"]
---

# 什麼是 Raycast 測試
# 什麼是 Raycast 測試

最近被精通各種密技的同事推坑開始使用 Raycast，結果被他強大的功能驚艷到！

之前其實也沒有用過像 Raycast 類似的工具，Raycast 有點像是「電腦的中央控制台」，你可以手指不用離開鍵盤，只要下簡單快速的指令，就可以控制電腦聽音樂、開啟軟體等等超多有趣的功能。

舉例來說，我今天想要 google search “木瓜營養成分”，這時候我會拿起滑鼠 → 點擊瀏覽器 → 點一下網址列 → 在鍵盤輸入“木瓜營養成分”按 Enter → 搜尋結果出現。

假如我用 Raycast 的話，直接用鍵盤隨便按一按，搜尋結果就出現（等等會詳細介紹），而這只是 Raycast 裡面一個最基礎的功能而已！

因為 Raycast 功能太多太強大，下面會分享一些我自己目前的使用方式，給入門的人一些參考，以免一打開被他複雜的介面嚇到。

# Raycast 基本設定

1. 首先到官網下載  [Raycast](https://www.raycast.com/) 


![Alt text](raycast%20site.png)

1. 安裝完成後打開 Raycast，這時會跳出 Raycast Setting 畫面， 這裡比較需要注意的是，快捷鍵設定（Raycast Hotkey)，Raycast 預設是 option + 空白鍵，因為這個快捷鍵對你之後叫出 Raycast 方便程度有很大的影響，我自己是直接使用預設，剛好沒有跟我其他快捷鍵打架。

![Alt text](Raycast%20Settings.png)

有的人已經有使用 Spotlight 快捷的習慣 （cammand + 空白鍵），基本上這個工具可以完全取代 Spotlight 甚至更好用，所以有的人會把它改成 cammand + 空白鍵，這裡就看自己的使用習慣。

# 1. Figma File Search 加速設計師找檔案的工作效率

Figma File Search 可以快速瀏覽 Figma 裡面海量的檔案，再也不用在一片 Figma 檔案海裡面，點進去點出來的尋找。甚至可以在 menu bar 上面就可以看到所有檔案（大推）！

首先先到 [Figma File Search](https://www.raycast.com/michaelschultz/figma-files-raycast-extension) 頁面，點擊 **Install Extension** 。

![Alt text](Raycast%20FIgma.png)

安裝完成後，接著打開 Raycast Setting / Extension 就會看到 Figma File Search，右邊視窗會顯示需要你輸入 **Personal Access Token** 和 **Team ID**。（我這邊已經輸入過，所以會顯示一堆圈圈）

![Alt text](Figma%20File%20Search.png)

#### Personal Access Token 在哪？

在 Figma.com 首頁的右上角點擊自己的頭像，開啟 Setting 後，往下滑會看到 Personal access tokens。

![Alt text](Figma%20Profile%20menu.png)

在 Add a token description 的文字輸入匡裡面，可以隨便取一個看得懂的名字，譬如：「Raycast 01」。按 Enter 之後就會產生一組 Personal access token，可以先複製貼到 Raycast（這個只能 Copy 一次，不小心關掉沒 copy 到，就 Revoke access 再重新創一個就好，莫驚慌。）

![Alt text](Figma%20Token.png)

#### Team ID 哪裡找？

範例：<https://www.figma.com/files/team/12345678987654321/Team?fuid=978491079863790852>

點擊上方連結以後，點擊自己公司用的 Teams 名稱，可以看到網址列上面 /team/ 後面這一串數字，

> figma.com/files/team/**這串數字就是你的 Team ID**/Team?fuid=978491079863790852...

以下方的例子來說， Team ID 就是 12345678987654321 這串數字。

![Alt text](Figma%20Team%20ID.png)

*這裡要提醒一下，這個 Extension 只能使用在 Figma Team 帳號，因為 Figma API 的限制所以目前 Drafts 沒有支援這個功能。*

#### 如何在 Menu bar 上新增 Figma Quick Search  

把 Personal Access Token 和 Team ID 都輸入後，然後記得在 Figma File Search / Quicklook 的右欄，點擊 **Activate** 
 ![Alt text](Raycast%20Figma%20Quicklook.png)
 
 這樣在 menu bar 上面的 figma 小 icon 就可以瀏覽所有 figma 檔案了！

 ![Alt text](Raycast%20Quicklook%20menubar.png)

#### 如何用 Raycast 找 Figma 檔案

點擊快捷 (option + space) 叫出 Raycast，輸入 figma (其實我輸入 f 就出現了，連快捷都沒設定就好聰明的自己跳出來)，點擊 Search File 就可以看到所有 Figma 檔案了，其他大家可以自己玩玩看。

![Alt text](Raycast%20Figma%20Search%20FIle.png)

剛剛最複雜的部分已經介紹完了，下面的操作方式就簡單很多。

# 2. Google Search 懶得用滑鼠點來點去時很好用

直接用 Raycast 操作 Google Search [這裡下載](https://www.raycast.com/mblode/google-search)，點擊 **Install Extension**

![Alt text](Raycast%20Google%20Search.png)

打開 Raycast (option + space) 輸入 goo 馬上可以看到 Google Search，Enter 之後輸入要查詢的東西按 Enter，搜尋結果直接出現！

![Alt text](Raycast%20Google%20Search%20Example.png)

> 這裡有一個小技巧，當你想快速叫出某功能的時候，可以在 Raycast Setting 裡面的 Extension 輸入 Alias（別名），這樣只要你一打 goo 就可以叫出 google search，或是設定輸入 trans 就可以叫出 google translate，可以輸入自己習慣的別名。

![Alt text](Raycast%20Alias.png)

# 3. Calculator 快速換算各國外幣

這是 Raycast 預設的 ectension 不用另外下載。

![Alt text](Raycast%20Calculator%20Icon.png)

在 Raycast 直接輸入「數字+幣名」，譬如 400 yen 或是 300 usd，他會直接幫你換算成新台幣。
蠻適合突然需要查幣別，不用再另外開瀏覽器或 app 查詢設定，方便！ 

![Alt text](Raycast%20Calculator%20example.png)

# 4. Spotify 非常適合小 Geek 使用

這邊我試用過兩個 Spotify Extension， 一個是 [Spotify Player](https://www.raycast.com/mattisssa/spotify-player) 和 [Spotify Beta](https://www.raycast.com/mattisssa/spotify-beta)。兩款各有各的好，所以我就先留著都用用看。

Raycast 支援的 Spotify 功能超多，像是看現在正在聽的音樂（Now Playing）、瀏覽（Browse All）等等不勝枚舉。

舉其中一個例子來說，下面是我正在聽的音樂，直接按 Enter 就可以暫停。

![Alt text](Raycast%20Spotify%20Example%2001.png)

按 command +K 有更多操作可以玩，像是暫停、上下首、開啟 Radio 等等

![Alt text](Raycast%20Spotify%20Example%2002.png)


# 5. 其他使用情境 

### Google Translate 
我之前都習慣用有道的 app 查詢翻譯，Raycast 也可以自動偵測你輸入的語言，直接換成中文。
![Alt text](Raycast%20Google%20Translate.png)

---

### Calendar
這個同事大推薦，可以在 menu bar 上面就看到自己接下來的行程，點進去還可以直接開啟 Zoom 或是 Google Meet 的會議連結。記得要在 **Show Events in Menu Bar** 設定成 **Always** 才會出現喔。
 ![Alt text](Raycast%20Calendar.png)

---

### System Monitor 

要是發現自己網路或是電腦變慢，可以打開來偵測一下系統的健康度。我自己原本有在用 iStat，常有事沒事會點開來看一下傳輸順不順暢或是哪個軟體在狂吃我的 CPU 或記憶體，但因為 iStat 要付費，或許這是另一個不錯的替代方案。

![Alt text](Raycast%20system%20monitor.png)

---

其他使用場景，像是在你突然要離開座位，想把螢幕鎖起還的時候，可以到 System / Lock Screen 關閉螢幕。或是當你突然有一個 idea 或是怕忘記某件事時，可以使用 Floating Note 立馬開一個浮動在桌面最上層的筆記。

# 結論

小時候覺得很會使用 terminl 的人很強，一般人開應用程式，會點開 Finder 再點應用程式，這樣很不帥。但是神人只要在 terminal 打幾行看不懂的程式碼，想找的東西就跳出來了，不禁內心充滿崇拜。

可能有人會想說，直接滑鼠點一點，比重新學習用 raycast 操作方便，那這個方式可能就不適合你ＸＤ。
我自己覺得這個學習曲線算是好上手，稍微習慣一下就可以立馬提升效率。

目前 Raycast 串接了超多服務，都可以在他的 [Store](https://www.raycast.com/store) 下載，重點是，目前個人使用完全免費的！除非你有協作的需求才要付費，非常推薦 Mac 使用者玩玩看！