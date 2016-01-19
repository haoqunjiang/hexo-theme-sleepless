![screenshot](https://cloud.githubusercontent.com/assets/3277634/12420377/33f53180-bef7-11e5-8e1e-9f441efd9aff.png)

## Install

``` bash
hexo init blog
cd blog
# grep -vE "hexo-renderer-ejs|hexo-renderer-stylus" package.json > tmpfile; mv tmpfile package.json
npm install
npm install --save hexo-renderer-jade hexo-renderer-sass hexo-autoprefixer hexo-generator-feed hexo-generator-sitemap hexo-browsersync
git clone https://github.com/sodatea/hexo-theme-sleepless.git themes/sleepless
```

## Enable Sleepless Theme

Edit `_config.yml`, set `theme` field as `sleepless`:

```yaml
theme: sleepless
```

## Update

``` bash
cd themes/sleepless
git pull
```

## Front-matter extensions

## Custom Blocks

### Warning Block

![Warning block screenshot](https://cloud.githubusercontent.com/assets/9530963/11359678/489a510c-92b9-11e5-9256-341cef6999b6.png)

Usage: `<p class="tip">Lorem ipsum dolor sit</p>`

## License

MIT
