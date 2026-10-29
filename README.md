# cv.shghgh.ir

Personal CV for Shayan Gholami. Plain HTML and one CSS file, with no build step and no dependencies.

```
index.html          the CV
css/style.css       shared styles (light/dark, mobile, print)
img/                photo, favicons, manifest
blog/               optional blog: index + post template
```

**Preview locally:** `python3 -m http.server`, then open http://localhost:8000

**Starting the blog:** copy `blog/hello-world.html`, edit it, list it in `blog/index.html`,
then uncomment the "Writing" link in the footer of `index.html`.
