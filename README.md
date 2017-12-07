# Luchian :paintbrush:

## [A Webpainter](https://commons.wikimedia.org/wiki/File:Luchian_-_Un_zugrav.jpg)

Luchian is xmc's frontend Semantic UI theme.

Named after Ștefan Luchian.

## Building luchian

1. Perform a normal Semantic UI install and navigate to your themes folder:
```bash
npm install semantic-ui
cd semantic/src/themes/
```
2. Clone this repo:
```bash
git clone https://github.com/xmc-dev/luchian
```
3. Edit your `themes.config` and replace `'default'` with `'luchian'` for every component you wish to theme:
```bash
nano ../theme.config
```
4. Build or watch with Gulp:
```bash
gulp build
gulp watch
```
