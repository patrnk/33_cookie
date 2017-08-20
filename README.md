# Frontend for SPA «ПомойАвто»

It is a frontend for single page application. Reach JavaScript is present.

# Deploy on localhost

Example of frontend launch on Linux, Python 3.5:

```bash
cd static/
python3 -m http.server 9000
```

Open page [127.0.0.1:9000](http://127.0.0.1:9000) in browser.

(The port 9000 is important because of CORS policy set up on server).

# Deploy on production server

This has to be deployed one of the following domains:
- `http://33_cookie.devman.org`
- `https://33_cookie.dev`
Other origins are prohibited by [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS).

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
