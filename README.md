# Glitchy website to advertise the ECPR public policy analysis mishaps panel

Inspired by https://codepen.io/acupoftee/pen/WNbBxXq, this creates a glitchy website to advertise a somewhat unique conference panel.

It's just HTML and CSS, so any static file server can host the page.

With Docker:

```
docker build -t glitch_page .
```

And the report can then be served to (for example) port 3200 with:

```
docker run -d -p 3200:3000 glitch_page
```
