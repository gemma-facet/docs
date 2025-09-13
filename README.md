# Facet AI Documentation

This is the documentation for Facet AI, a no-code web platform where you can easily fine tune the Gemma family of vision and small language models for your task and domain specific adaptations, without worrying about dataset formatting, cloud engineering, training algorithms — you can get started from scratch in a few minutes with little programming & AI experience!

## Contributing

Missing content? Open an issue or submit a pull request. We also welcome feedback and suggestions! Feel free to create new tutorials and guides to help others learn how to use Facet AI as well!

## Development

Our docs use Mintlify, a tool for building beautiful documentation sites.

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```bash
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json` (from the root of this repo)

### Resources

- [Mintlify documentation](https://mintlify.com/docs)
- [Mintlify community](https://mintlify.com/community)
