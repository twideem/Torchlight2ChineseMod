# Torchlight II Chinese Mod

本模組修改自：

Steam 工作坊 :: Chinese Language Package

http://steamcommunity.com/sharedfiles/filedetails/?id=137931397

這原本是設計給 Steam 版玩家用的中文化，但艾玩天地版的玩家也推薦使用，因為官方中文有許多疏漏的地方，像是 BOSS 的隨機名字沒做出來、簡字繁字混用、還導致編碼錯誤漏字、有的有翻有的沒翻。這個中文化包，內含 3DM 模組版中文化、巴哈姆特 Matif 修正版官方中文化，大幅修改上述問題，且字體更精美，改用這模組會有更美好的遊戲體驗！

不過，像是 3DM 版中文模組翻譯品質很高，但用語是中國大陸，台灣玩家看起來不自然。基於台灣官方中文的 Matif 版模組，剩三處錯誤沒修正到。美化用的字型，使用檔案很小但版本較舊的文泉驛微米黑，優點是解決當機的問題，缺點是不支援半形空格。因此我另外修改出這份中文化包。

## 內容

* Chinese[CN]

  3DM 版簡體中文。原封不動，其實看簡體字的話，就覺得大陸用語很自然了～

* Chinese[TW]

  Matif 版繁體中文。修正剩下的三個漏字，並重翻中英混用的地方，像是偷取生命時顯示 +HP，偷取法力時卻顯示 +魔法值。台灣玩家建議使用這個中文化。

* Chinese

  以 Matif 版繁體中文為主，依我個人喜好修改用語，像是開始畫面、名聲、以及牧牛人領地。屬於私人偏方，不建議使用。

## 如何使用

將 bin 資料夾裡的 CHINESE.MOD，放在 [使用者文件]\My Games\Runic Games\Torchlight 2\mods 裡面，並以掛載模組的方式，掛載本中文化進行遊戲。

如果你想修改本模組，原始檔放在 src 資料夾裡面，可用遊戲隨附的編輯器 GUTS 製作成模組。

## 注意

行尾空白與否，視為不同項目，所以用文字編輯器修改 src 檔案的話，不要啟用存檔刪除結尾空白的功能！

## Chinese[CN] 或 Chinese[TW] 的修正內容

      [TRANSLATION]
        <STRING>ORIGINAL:Rawhide Caubeen
        <STRING>TRANSLATION:生皮貝雷帽
      [/TRANSLATION]

      [TRANSLATION]
        <STRING>ORIGINAL:The Song of Slaying
        <STRING>TRANSLATION:殺戮之歌
      [/TRANSLATION]

      [TRANSLATION]
          <STRING>ORIGINAL:"Wow! You're not dead?"
          <STRING>TRANSLATION:「噢，你還沒死啊！」
      [/TRANSLATION]

      [TRANSLATION]
        <STRING>ORIGINAL:Thank you for rescuing me.  I had recovered the |cFFD1FF7APasskey Ember|u from these slavers, but they captured me as I was trying to return to the Enclave.\n\nI know that you are trying to reach the |cFFD1FF7AWatchweald Temple|u, but I could use your help with one small matter before you go.  These slavers have been harrying the Estherians for several weeks now.  You defeated many, but there are many more watching us from the safety of those huts.  Burn them out!  If they are allowed to remain, the Frosted Hills will never be safe.
        <STRING>TRANSLATION:多謝你救了我！我從這些奴隸販子手裡奪回了|cFFD1FF7A燼石鑰匙|u，不過我在回聚居地的路上卻被他們抓住了。\n\n我知道你正要前往|cFFD1FF7A戒林神廟|u，但是我十分需要你的幫助。這些奴隸販子好幾周以來都一直在綁架我們埃塞利亞人。你已經擊敗過他們了，但是還有很多躲在那些草屋裡，對我們虎視眈眈。燒死他們吧！如果不消滅他們，霜凍山丘用不得安寧。
      [/TRANSLATION]

      [TRANSLATION]
        <STRING>ORIGINAL:HP
        <STRING>TRANSLATION:生命
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:MP
        <STRING>TRANSLATION:法力
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Mana
        <STRING>TRANSLATION:法力
      [/TRANSLATION]

      [TRANSLATION]
        <STRING>ORIGINAL:ACT II
        <STRING>TRANSLATION:第二章
      [/TRANSLATION]

      [TRANSLATION]
        <STRING>ORIGINAL:ACT III
        <STRING>TRANSLATION:第三章
      [/TRANSLATION]

      [TRANSLATION]
        <STRING>ORIGINAL:ACT IV
        <STRING>TRANSLATION:第四章
      [/TRANSLATION]

      [TRANSLATION]
        <STRING>ORIGINAL:Generates Shock Copters
        <STRING>TRANSLATION:產生電擊直升機
      [/TRANSLATION]

      「殘破礦井s」改為「殘破礦井」。

* 字型改用懷源黑體的 KaiGenGothicTW-Bold.ttf，解決不能使用半形空格的問題。

## Chinese 的修改內容

      [TRANSLATION]
        <STRING>ORIGINAL:Unrecognized
        <STRING>TRANSLATION:默默無名的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Barely Known
        <STRING>TRANSLATION:初出茅廬的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Recognized
        <STRING>TRANSLATION:得到賞識的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Tolerated
        <STRING>TRANSLATION:經得起考驗的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Acknowledged
        <STRING>TRANSLATION:眾所認可的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Respected
        <STRING>TRANSLATION:眾所推薦的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Well-Known
        <STRING>TRANSLATION:印象不錯的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Liked
        <STRING>TRANSLATION:印象很好的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Memorable
        <STRING>TRANSLATION:印象深刻的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Honored
        <STRING>TRANSLATION:與有榮焉的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Prominent
        <STRING>TRANSLATION:志得意滿的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Local Hero
        <STRING>TRANSLATION:嶄露頭角的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Widely Known
        <STRING>TRANSLATION:眾所周知的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Remarkable
        <STRING>TRANSLATION:萬人矚目的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Ascendant
        <STRING>TRANSLATION:大展鴻圖的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Distinguished
        <STRING>TRANSLATION:聲名大譟的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Prestigious
        <STRING>TRANSLATION:享有聲望的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Eminent
        <STRING>TRANSLATION:功名顯赫的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Folk Hero
        <STRING>TRANSLATION:受人愛戴的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Famous
        <STRING>TRANSLATION:遠近馳名的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Acclaimed
        <STRING>TRANSLATION:家喻戶曉的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Local Legend
        <STRING>TRANSLATION:市民景仰的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Illustrious
        <STRING>TRANSLATION:舉國歡騰的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Renowned
        <STRING>TRANSLATION:舉世無雙的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Celebrated
        <STRING>TRANSLATION:垂名青史的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Lionized
        <STRING>TRANSLATION:流芳千古的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Glorious
        <STRING>TRANSLATION:偉人的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Legendary
        <STRING>TRANSLATION:傳奇的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Exalted
        <STRING>TRANSLATION:聖人的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Fabled
        <STRING>TRANSLATION:傳說的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Mythic
        <STRING>TRANSLATION:神話的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Immortal
        <STRING>TRANSLATION:不朽的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Demigod
        <STRING>TRANSLATION:神人的
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Unattainable
        <STRING>TRANSLATION:無上的
      [/TRANSLATION]

      [TRANSLATION]
        <STRING>ORIGINAL:Load
        <STRING>TRANSLATION:讀取
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Resume
        <STRING>TRANSLATION:繼續
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:New Game
        <STRING>TRANSLATION:新建
      [/TRANSLATION]

      [TRANSLATION]
        <STRING>ORIGINAL:Single Player
        <STRING>TRANSLATION:單機
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:Internet
        <STRING>TRANSLATION:線上
      [/TRANSLATION]
      [TRANSLATION]
        <STRING>ORIGINAL:LAN
        <STRING>TRANSLATION:區網
      [/TRANSLATION]

      [TRANSLATION]
        <STRING>ORIGINAL:Play
        <STRING>TRANSLATION:開始
      [/TRANSLATION]

* 「牧牛人領地」改為「冥界之地」。
* 「異域行者」改為「漂泊者」。
* 「怒氣」改為「充能」。
* 「猛擊」改為「處決」。

## 其他

* 我喜歡遊戲畫面原本乾淨的樣子，所以沒有提取打上蒹葭汉化组廣告和中文化的過場圖像。
* 不想讓語言選單顯得雜亂，所以讓 Chinese[TW] 和 Chinese[CN] 取代了 Traditional Chinese 和 Simplified Chinese 的位置，想恢復官方中文的話移除 MOD 即可。