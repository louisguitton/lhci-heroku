# lhci-heroku

> Heroku-based LHCI Server - louisguitton-lhci.heroku.com

Ref: https://github.com/GoogleChrome/lighthouse-ci/blob/main/docs/recipes/heroku-server/README.md

## updating LHCI

```sh
# Update LHCI
npm install --save @lhci/server@latest
# Create a commit with your update
git add package.json && git commit -m 'update LHCI'
# Deploy your update to heroku
git push heroku main
```
