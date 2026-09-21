# test-html

Minimal test page for the `idpay-b2b-sdk` (ByUnicoSDK).

## Run

```sh
npx serve .
```

Open `index.html` with `token` and `processId` as query params:

```
http://localhost:3000/?token=YOUR_JWT&processId=YOUR_TRANSACTION_ID
```

Both are read from the URL and passed to `ByUnicoSDK.init` / `ByUnicoSDK.open`.
