# py2022
2022 資訊之芽北區、竹區 py 班課程網站

## 開發方式
1. 先參考 [Jekyll 官網](https://jekyllrb.com/docs/installation/)，安裝 Ruby、Gem、Jekyll 等套件
2. 透過 `Gemfile` 安裝此專案的相依套件
    ```bash
    bundle install
    ```
3. 編譯網站，並在 <http://127.0.0.1:4000/> 建立網頁服務
    ```bash
    bundle exec jekyll serve
    ```

## 設定方式
- 各個 `.md` 檔案將被編譯成 HTML 檔，例如 `slides.md` 會變成 `<url>/slides.html`，在 GitHub Pages 也可透過 `<url>/slides` 存取
- 上方導航列（navbar）可透過 `_config.yml` 的 `navbar_items` 設定
    - 較複雜的部分可直接在 `_includes/navbar.html` 更改
