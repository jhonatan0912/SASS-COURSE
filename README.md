- Install sass as a dev dependency

```console
  $ npm i sass -D
```
- Wath files with sass extension and convert them into css folder

```console 
  $ sass --watch sass:css 
```

- Add partials
```js 
 _filename // add _ on the name start
```
- Call partial in the main file
```js
  @use 'filename'; // without _ at start of name
```