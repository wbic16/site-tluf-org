# site-tluf-org — the tluf.org site source of record

The live site for [tluf.org](https://tluf.org): Assay's front door.
TLUF = Truth · Lies · Uncertainty · Fiction — the four bins every assessed
claim is filed under.

- `index.html` — the front page (T.L.U.F. banner design; SHA-256
  aa114fe365c6d32e3f1a57e512b2d073d4b4c6ed56f008f4d5656366d31e8014).
- `submit.html` — "Submit a paper resource" (SHA-256
  c63dbf8c4b8a02222dd008e6944da9acc07ebb2a122152c292384e148ac9534f). Its
  client canonicalizer is embedded verbatim from `canon.js` in
  [wbic16/moat](https://github.com/wbic16/moat) (`service/`), which is also
  where the submissions backend lives.

Deployment: awsbox docroot `/sites/web/tluf.org/`, files at mode 644.
The full deployment map — which repo deploys what, the service unit, and
the one outstanding root step — is `DEPLOY.md` in wbic16/moat.
