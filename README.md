# HANDs Art Project 

推手計劃網站前端切版

> A frontend project for hands Taiwan

## Build Setup

``` bash
# install dependencies
npm install

# build for developmemt (編譯的 css 不是 minify)
npm run dev

# build for production with minification
npm run prod

# watch
npm run watch

```

## Style Guide
- `index.html`

## Pages
- `collection-blog.html`
- `collection-blog-category-tag.html`
- `collection-artist.html`
- `page-artist.html`

## Files
- `assets/` 第三方套件及照片
- `dist/` 編譯好的檔案
- `src/` 開發使用的檔案

## Mixin
breakpoint 
- xsmall 500px
- small 768px
- medium 1024px
- large 1200px
> ```
> @include breakpoint('medium') {
>     
> }
>```

>```
> @media (max-width: 1024px) {
>      
> }
>```
