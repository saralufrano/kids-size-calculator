# kids-size-calculator

Tiny clothes + shoe size calculator, with Capacitor ready for iOS and Android.

## Mobile setup

```bash
npm install
npm run cap:add:ios
npm run cap:add:android
```

## App icon + splash assets

The source logo lives in `assets/logo.svg`.

After the native projects exist, generate the iOS + Android icons and native splash assets with:

```bash
npm run assets:generate
```

The native splash uses the pale blue background + `12M → ?` mark. The app then shows the full `What size will they be? / Stop doing baby math in public.` launch screen briefly before the calculator.

## Sync and open

```bash
npm run cap:sync
npm run cap:open:ios
npm run cap:open:android
```

`npm run cap:sync` copies the latest `index.html` into both native apps.
