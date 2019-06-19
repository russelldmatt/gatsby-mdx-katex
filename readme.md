# Trying to get gatsby + mdx + katex working

Created via:
```sh
npm init mdx gatsby gatsby-mdx-katex
```

Then added katex via:
```sh
npm install --save gatsby-transformer-remark gatsby-remark-katex katex
```

Then updated the gatsby-config:
```sh
git show b137d863ceb2770269a971ef494f9392057ebbad gatsby-config.js
```

And the index.mdx:
```sh
git show b137d863ceb2770269a971ef494f9392057ebbad src/pages/index.mdx
```

Restarted the gatsby development server:
```sh
git develop
```

Went and looked at http://localhost:8000/ and my equation was just plaintext with surrounding dollar signs.  

Any help would be appreciated!
