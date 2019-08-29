![Screenshot](https://raw.githubusercontent.com/syzlmr/milling-gcode-snippet/master/images/gcode.gif)

## このエクステンションの特徵

1. このエクステンションはCNCフライス盤のGコード高速入力とさまざまなGコードパラメータ記述機能を提供します。
2. このエクステンションは、X、Y、Z、A、B、C、U、V、W軸の小数点検査機能が付いています。
3. 色が濃いほど重要です。例えば、赤色の文字は特に注意しないといけないところです。（例：小数点が抜けている場合など）

[中文影片範例](https://www.ehosei.com/gcode-quick-editing)說明程式簡寫及高亮等設定方式。  

## 使用命令
簡寫命令| 命令意義 |
:-------:|:-----: |
gs     | 程式開始定型文 |
gms    | 程式中新刀開始定型文 |
gme    | 程式中舊刀結束定型文 |   
ge     | 程式結束定型文 |
gc     | 註解 |
g(軸)  | 括號處填入X,Y等軸向 |
o      | 插入程式號O代碼 |
n      | 插入N代碼 |
t      | 插入T換刀代碼 |
g00~g99| 插入G碼(g需為小寫)。輸入g後未按Enter確定前，會出現該G碼定義。|

## 使用方法

安裝並啟動此套件. 當您在視窗右下方設定語言為 `gcode` 或儲存檔案名稱為 `.nc` 相關檔案時將驅動此套件。中文說明先按 `g` 即可出現輔助精靈。

## 安裝

由Vscode Marketplace下載安裝。

## TODO

- 新增Macro支援。
- 新增Renishaw量測Macro。

## 免則聲明

本套件免費提供CNC銑床G碼快速輸入及銑床G碼參數說明功能。本套件不暗示、不聲明或不保證其內容之正確性或可靠性，使用者應自行判斷與承擔風險。

## License

松本　明諭のこのエクステンションは[MIT License](https://opensource.org/licenses/MIT)を守って、無料で配布しています。

