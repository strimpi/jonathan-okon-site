# Deploy (GitHub Pages)

No edits needed in index.html. LinkedIn is already set and no GitHub username appears in the page.

1. GitHub: new public repo (name it USERNAME.github.io for a root URL).
2. Upload the CONTENTS of the folder (index.html, photo.jpg, certs/, thumbs/) -> Settings > Pages > Deploy from branch: main / root.
3. search.google.com/search-console -> Add property (URL prefix) -> verify via HTML tag (paste in the marked spot in <head>) -> URL Inspection -> Request Indexing.
4. Test schema: validator.schema.org with your live URL.

Note: the live address of a GitHub Pages site always contains the account name (USERNAME.github.io). To keep it out of the address, you need a custom domain (Settings > Pages > Custom domain).
