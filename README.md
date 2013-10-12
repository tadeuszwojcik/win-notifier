# win-notifier

  Easy to use notifications for javascript(WinJS etc) windows store apps, no more handcrafting xml in javascript!

## Installation

```
$ npm install win-notifier
```

or

copy file index.js and reference it manually into the project.

## Usage

### Toast notification:

#### examples
```js
  winNotifier.showToast({
      toastText01: {
          text1: 'Hello!'
      }
  },{
      silent: true,
      tileId:'secondaryTileId'
  });
```

## License

  [WTFPL](LICENSE.txt)
