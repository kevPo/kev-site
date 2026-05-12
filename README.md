# kev-site

Static personal site for Kevin Poston.

## Local Preview

```sh
python3 -m http.server 4173
```

Then open:

```text
http://127.0.0.1:4173/
```

## Netlify

This site does not need a build command. In Netlify, connect the GitHub repo and use:

- Build command: leave blank
- Publish directory: `.`

The same settings are captured in `netlify.toml`.
