## Runlight

Analytics that lives inside your app.

Runlight is privacy friendly web analytics that you run yourself. It counts visitors without cookies and without storing anyone's IP address, so there's no consent banner to show. The numbers stay in your own database, and the dashboard is served from your own domain. MIT licensed.

**[runlight.sh](https://runlight.sh)** · [Docs](https://runlight.sh/docs/) · [Changelog](https://github.com/runlightsh/runlight/blob/main/CHANGELOG.md)

### Install

| Language | Install |
|---|---|
| TypeScript and JavaScript | `npm install @runlight/sdk better-sqlite3` |
| Standalone server | `npx runlight.sh`, or `docker run -p 3000:3000 -v runlight:/data ghcr.io/runlightsh/runlight` |
| PHP | `composer require runlight/runlight` |
| Python | `pip install runlight` |
| Ruby and Rails | `bundle add runlight` |
| Go | `go get runlight.sh/go` |
| Java | `sh.runlight:runlight` |
| .NET | `dotnet add package Runlight.AspNetCore` |
| Elixir | add [`:runlight`](https://hex.pm/packages/runlight) to `mix.exs` |
| Rust | `cargo add runlight` |

There are also plugins for [WordPress](https://runlight.sh/docs/wordpress/), [Drupal](https://www.drupal.org/project/runlight), and [Craft CMS](https://runlight.sh/docs/craft/), and an MCP server so AI apps can answer questions about your numbers.

### Repositories

- **[runlight](https://github.com/runlightsh/runlight)**: every package, the plugins, and the docs. Issues and pull requests go here.
- [runlight-php](https://github.com/runlightsh/runlight-php) and [runlight-craft](https://github.com/runlightsh/runlight-craft): read-only copies of the PHP package and the Craft plugin, for Packagist and the Craft Plugin Store.
