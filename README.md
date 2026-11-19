# itmly for Cursor

Know your stuff, just by asking.

[itmly](https://itmly.app) keeps a calm, complete record of the things you own: what you bought, where it lives, what it is worth, and who has borrowed it. This plugin connects Cursor to your itmly catalogue so you can look things up and keep it current without leaving your editor.

## What you can ask

- "Add everything I bought this month."
- "What is my camera gear worth?"
- "Who has my drill?"
- "Find the items that still need a photo, and fill them in."

## Install

1. Install **itmly** from the Cursor Marketplace.
2. The first time Cursor uses it, you will be asked to sign in to itmly and approve access.
3. That is it. Your catalogue is now one question away.

Prefer to set it up by hand? Add this to your `mcp.json`:

```json
{
  "mcpServers": {
    "itmly": {
      "url": "https://itmly.app/api/mcp"
    }
  }
}
```

## Your data, your call

- Reads by default. Changes only with your approval, and it asks before deleting.
- You sign in with your itmly account on an itmly screen, so your password never reaches Cursor. This plugin stores no passwords or keys.
- Your assistant sees only your items.
- Disconnect anytime by removing itmly in Cursor's settings.

Read more at [itmly.app/mcp](https://itmly.app/mcp) and in our [privacy policy](https://itmly.app/privacy).

## What is in this repository

| File | Purpose |
| --- | --- |
| `.cursor-plugin/plugin.json` | Plugin manifest |
| `mcp.json` | Points Cursor at the hosted itmly server, `https://itmly.app/api/mcp` |
| `assets/logo.png` | itmly logo |

The itmly server itself is hosted by Holy Schmitt Studios. This repository only contains the connection details, so there is nothing to build or run.

## Support

Questions or problems: [help@itmly.app](mailto:help@itmly.app) or [itmly.app/support](https://itmly.app/support).

## License

MIT. See [LICENSE](LICENSE).
