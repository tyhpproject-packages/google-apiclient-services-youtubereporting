<!-- tyhp-readme:start -->
# tyhpdef/google-apiclient-services-youtubereporting

Tyhp type definitions for `google/apiclient-services` `0.459.0`.

```bash
composer require --dev tyhpdef/google-apiclient-services-youtubereporting:0.459.0
```

This is a metapackage. Composer also installs `tyhpdef/google-apiclient-services-youtubereporting-impl` (type files).
Require **this** name, not `tyhpdef/google-apiclient-services-youtubereporting-impl`.

See https://tyhplang.com.

## Maintain `google/apiclient-services`? Ship the types yourself

If you are a Packagist maintainer of `google/apiclient-services`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/google-apiclient-services-youtubereporting-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `google/apiclient-services` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/google-apiclient-services-youtubereporting": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `google/apiclient-services` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `google/apiclient-services` with a real constraint,
   `"replace": { "tyhpdef/google-apiclient-services-youtubereporting": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `google/apiclient-services` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/google-apiclient-services-youtubereporting` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
