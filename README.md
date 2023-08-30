# Search Material Symbols icons (Outlined)

一個用於查詢 `Material Symbols icons` 的工作流，可自訂查詢關鍵字 (預設為`mdi`)

![usage](./images/usage.png)

## Configuare

先在 Workflow 列表中找到此工作流，右側 Workflow 的視圖區域上方，在顯示工作流名稱的下面有個 `Configuare Workflow`，`Search Keyword` 是觸發 Workflow 的關鍵字 (預設:`mdi`)

## Usage

`mdi ${查詢關鍵字}`

## 其他事項

查詢結果中的 icon 是 npm 庫`@material-symbols/svg-400`內的 SVG 圖檔，經`svg-fill`將其改為白色後另存的副本檔案，並且此流程運作也是將查詢關鍵字與 SVG 圖檔名稱進行篩選後得出的結果。

查詢結果最終將複製到剪貼簿中，以利在 HTML 中使用，正常情況下使用`material icons`的方法為在網頁中加入`<span class="material-symbols-outlined">$ICON_NAME</span>` 將查詢結果的文字替換`$ICON_NAME`即可

目前此功能查詢的 icon 僅有`@material-symbols/svg-400/outlined`，且不包含`FILL`的 SVG，後續有其他需求再考慮調整。現階段覺得已經十分夠用。
