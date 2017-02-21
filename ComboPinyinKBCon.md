宮保拼音·鍵盤控式
===

簡介
---

[[宮保拼音|ComboPinyin]] 是一種爲 PC 鍵盤設計的多鍵並擊輸入拼音的方法。

本式改進了原《宮保拼音》方案（以下稱其爲「大衆式」），將其應用於拇指位有左右各一按鍵的特製鍵盤，
進一步優化了組合聲母的指法，使左手的操作難度和思維負擔減輕，從而提高舒適感。（見文末創作者自我測評）

本方案共使用 20 枚按鍵，以雙手除小指外的 8 個手指並擊 1 ~ 6 枚不等的按鍵。

佈局
---

        Ln  Dt          u   I   O
    S   Cr  Z*  Gk      i*  N   E
        Fm  Bp      er  yu  U   E'
                H*  A*

    標「*」的按鍵爲拇指、食指的基準鍵位

說明：聲母部分已精簡並重新排列，`G` 與 `S` 匹配 QWERTY 鍵盤的 G 鍵與 S 鍵，高頻的 `Z`、`C`、`S` 安置在定位行。

組合鍵
---

「鍵盤控式」組合聲母

    BH = p, BF = m, DH = t, DL = n, GH = k,
    ZH = zh, CH = ch, SH = sh, ZC = r

說明：聲母 `p`、`t`、`k` 由 `b`、`d`、`g` 組合作爲送氣標記的 `h` 並擊輸入；`zh`、`ch`、`sh` 直觀地取漢語拼音的寫法。
次濁聲母 `m`、`n`、`r` 以食指、中指並擊同一排（同屬一組聲母）的兩枚聲母鍵。

組合韻母及活用（同「大衆式」），括弧內爲活用組合

    AI = ai, EI (OI) = ei, AU = ao, U (E'U) = ou,
    uI = uei, uAI = uai, iU (yuU) = iou, iAU (yuAU) = iao,
    N = en, NE = eng, AN = an, ANE = ang,
    iN = in, uN = uen, yuN = yun,
    iNE = ing, uNE (uIO) = ong, yuNE (yuUE') = iong,
    uANE (uAIO) = uang

適用鍵盤型號及固件
---

理論上凡左右手拇指位各有一可編程按鍵者皆可使用。
筆者已將本式宮保拼音用於以下鍵盤型號：

  - AMJ40:   http://github.com/lotem/AMJ40/tree/kbcon
  - ErgoDox: http://github.com/lotem/ergodox-firmware/tree/kbcon

預設鍵位左手拇指爲回車鍵，通過佈局切換鍵開啓「宮保拼音」佈局後，左手拇指位變爲「`;`」鍵，對應宮保拼音碼 `H`。

本式宮保拼音亦可用於標準 PC 鍵盤，對其兼容的佈局和指法詳見下文。

本式用於 PC 鍵盤時，因爲用到中排第 1 列左手小指控制下的按鍵參與並擊，經實驗發現在一些鍵盤上更容易發生按鍵衝突。因此相對於「大衆式」，本式對鍵盤的並擊性能更爲挑剔。

「鍵盤控」兼容佈局
---

該佈局是對「鍵盤控式」宮保拼音佈局的擴展，使其適用標準 PC 鍵盤。
主要區別是不使用左手拇指位 `H` 鍵，而改用主鍵盤區中排第 1 列字母鍵，由左手小指操作。

仍由同一個輸入方案 `combo_pinyin_kbcon` 實現，無須切換輸入方案。

        C'  Ln  Dt  T'      u   I   O
    H'  S   Cr  Z*  Gk      i*  N   E
        Z'  Fm  Bp  P'  er  yu  U   E'
                        A*

    標「*」的按鍵爲拇指、食指的基準鍵位

組合鍵增補
---

「鍵盤控式」組合聲母（同上）

    BH = p, BF = m, DH = t, DL = n, GH = k,
    ZH = zh, CH = ch, SH = sh, ZC = r

PC 鍵盤組合聲母及活用

    BH' (BZ') = p, BF = m, DH' (DC') = t, DL = n, GH' (GC) = k,
    ZH' (ZS) = zh, CH' = ch, SH' = sh, ZC = r

兼容「大衆式」聲母

    P' = p, T' = t, FZ' = zh, LC' = ch, CS = sh

組合韻母及活用（同上、亦同「大衆式」）

    AI = ai, EI (OI) = ei, AU = ao, U (E'U) = ou,
    uI = uei, uAI = uai, iU (yuU) = iou, iAU (yuAU) = iao,
    N = en, NE = eng, AN = an, ANE = ang,
    iN = in, uN = uen, yuN = yun,
    iNE = ing, uNE (uIO) = ong, yuNE (yuUE') = iong,
    uANE (uAIO) = uang

創作者自我測評
---

筆者由「大衆式」切換到「鍵盤控式」以來，打字技巧又有所提高。

主觀感受是按鍵更省力、對思維的干擾也小一些。略加練習已經可以跟打節奏較爲舒緩的歌詞了。

https://www.youtube.com/watch?v=Qsvtb4oNwoQ

這歸因於本式佈局和指法簡化、規律性更強、更充分地利用了拇指的優勢並擊能力。