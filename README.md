This repo contains the legacy implementation of $fh.sec for FeedHenry Rhino apps.

To use, just drop sec.js file in the app and reference it in the app.

It can be used with the JS SDK or standalone. If it's used with JS SDK, make sure it's loaded AFTER js sdk to make sure it will override $fh.sec default implementation.

If it's used standalone, please note hash function won't work as it's using $fh.hash from JS SDK.

See sec_test.js for example usage.

