# Inspector Documentation

Documentation for Inspector - the visual editor for your front-end.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview documentation changes locally:

```
npm i -g mint
```

Run at the root of the documentation (where `docs.json` is located):

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Changes are deployed to production automatically after pushing to the default branch.

## Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

## Resources

- [Inspector Website](https://tryinspector.com)
- [Discord Community](https://discord.gg/inspector)
- [Mintlify documentation](https://mintlify.com/docs)
