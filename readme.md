
論文樣板 project

使用 [pandoc](http://pandoc.org/) 轉換

由標記語言 Markdown 轉換為 Latex

最後再由 Xelatex + Bibtex 製成 PDF

--------

requirements:

- leo editor
- xelatex + bibtex
- pandoc

---------

User guide

- 在 `#content` 節點，下新增論文章節內容
- 在 `#refer` 節點，新增參考文獻
- 在 `#appendix` 節點，新增附錄
- 在 `#content` 節點下的 `settings` 節點，調整設定（如：論文題目）
- 使用 `makepdf` 按鈕於 `tmp\` 資料夾下產生 pdf
- 使用 `clean` 按鈕於 `tmp\` 資料夾清理所有檔案
