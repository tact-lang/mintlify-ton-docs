# Mintlify Starter Kit

> Preservation...

**[Follow the full quickstart guide](https://starter.mintlify.com/quickstart)**

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```
npm i -g mint
```

Alternatively, run `npx mint` instead. Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
# or
npx mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

[Mintlify's GitHub app](https://dashboard.mintlify.com/settings/organization/github-app) is connected to this repository. Thus, changes are deployed to production automatically after pushing to the default branch (`main`).

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- [Mintlify documentation](https://mintlify.com/docs)
- [Mintlify community](https://mintlify.com/community)
