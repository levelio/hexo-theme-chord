# hexo-theme-chord

## Installation
Install theme and renderers:

```
git clone https://github.com/Simlesos/hexo-theme-chord.git themes/chord
npm install hexo-renderer-sass --save
npm install hexo-render-pug --save
npm install hexo-generator-feed --save
```

Then change your `theme` setting in `_config.yml` to `chord`.

## Configuration
Default config:

```
logo: ## site logo path
duoshuo: ## duoshuo_shortname
ga: ## Your Google Analytics tracking id
menu:
  - page: home
    directory: /
  - page: archive
    directory: archives/
  - page: about
    directory: about/
  - page: rss
    directory: atom.xml
```