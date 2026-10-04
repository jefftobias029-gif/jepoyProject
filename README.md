# My Projects

One repository for all my web apps. Each app lives in its own folder under `apps/`.

| App | Description |
| --- | --- |
| [quotation-tool](apps/quotation-tool) | Quotation builder with Google Sheets and Drive integration |

## Adding a new app

```bash
cp -r apps/_template apps/my-new-app
```

Then add a row to the table above and commit.

## Hosting

Enable GitHub Pages (Settings, Pages, deploy from `main`). Each app is then at
`https://<username>.github.io/<repo>/apps/<app-name>/`.
