# dodendi website

Published copy of the dodendi shop site, served at https://dodendi.com (GitHub Pages, custom domain set by the `CNAME` file; https://nkhvuuu.github.io redirects there).

`index.html` is the built page without the Shop admin (`v13/dodendi-v13-public.html` in the private source repo). Products are edited in the Claude artifact at https://claude.ai/artifact/XXn98smGGnhUtHh9PKC8sD; to update this site, pull that state into the source repo, rebuild there and copy the public build here as `index.html`.

The shop admin is at /admin.html (sign-in for the owner and helpers; products and photos live in Supabase). Built from the dodendi-website repo, `v14/build.py`.
