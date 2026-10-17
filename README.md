# Tonen for Claude Code (retired)

This plugin is retired. Tonen now works with your coding agent through its MCP server, so there's nothing to install from here: you sign in once, and the agent sets Tonen up in your site, reads its comments, and marks them fixed.

## Claude Code

```
claude mcp add --transport http tonen https://tonen.app/mcp
```

Then `/mcp` in Claude Code, pick `tonen`, sign in and Allow. `/mcp__tonen__setup` adds Tonen to the project you're in; `/mcp__tonen__fix` works through its comments.

## Codex

```
codex mcp add tonen --url https://tonen.app/mcp
codex mcp login tonen
```

Then ask Codex to set up Tonen.

## If you installed this plugin

Remove it with `/plugin uninstall tonen@tonen` and `/plugin marketplace remove tonen`. Its `/tonen:share` added a script tag from `tonen-mvp.web.app`, an earlier version of Tonen: take that tag out of your site before you set it up again through the MCP.
