# Pingram Homebrew tap

Homebrew requires a separate tap repo named `homebrew-*`. Binaries still come from [pingram-io/cli releases](https://github.com/pingram-io/cli/releases).

Public tap repo: [pingram-io/homebrew-cli](https://github.com/pingram-io/homebrew-cli) (`Formula/pingram.rb`)

```bash
brew install pingram-io/cli/pingram
```

Or:

```bash
brew tap pingram-io/cli
brew install pingram
```

Formula source of truth in the Pingram monorepo: `sdks/cli/homebrew/pingram.rb`.
