# 粵語量詞資料庫

## 說明

本倉庫提供[開放詞典](https://kaifangcidian.com/han/yue)的**粵語量詞詞典**數據，旨在搜羅粵語口語與書面語量詞、動量詞以及與之搭配的名詞、動詞儘量，方便各界人士查詢並再用。

## 數據格式

數據儘可能用一個簡單的純文本格式排列：每詞條以換行符（`\n`）分割，詞條裡每一列則以製表符（`\t`）分割。

### 原始數據文檔

量詞數據包含在`data`目錄裡的文本文件，如下：

* `yylc.txt`: **量詞列表**
* `yylc_dp.txt`: **量詞搭配表**
* `yy_dlc.txt`: **動量詞列表**
* `yy_dlc_dp.txt`: **動量詞搭配表**

### 拼音方案

原始數據使用的粵語拼音方案為改良（九調）的耶魯拼音，不過`dist`目錄裡含有各種格式的資料以方便慣用其他方案的人也能夠儘量無障礙地使用此數據。

### 其他格式

數據以耶魯、粵拼等11種粵語拼音方案、以及 TSV、CSV、MD 等多種文檔格式發佈，各種形式可以在`dist`目錄裡的子目錄找到。

若想瀏覽數據，可以在 [MD 目錄]裡查看數據的可視化表格。

## 實現示例

* JavaScript

## 另見

* [粵語拼音轉換表](https://github.com/kfcd/pingyam) 和 [pingyam-rb](https://github.com/dohliam/pingyam-rb) （用來轉換數據拼音）

## 版權

© 2015 [開放詞典](http://www.kaifangcidian.com)

本表依照創作共用（創用CC/知識共享）姓名標示（署名）協議發佈。

<a rel="license" href="http://creativecommons.org/licenses/by/3.0/"><img alt="創用 CC 授權條款" style="border-width:0" src="https://i.creativecommons.org/l/by/3.0/88x31.png" /></a><br />本著作係採用<a rel="license" href="http://creativecommons.org/licenses/by/3.0/">創用 CC 姓名標示 3.0 未本地化 授權條款</a>授權.
