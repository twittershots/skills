# TwitterShots Skill

A Agent Skill for generating high-quality screenshots of Twitter/X posts.

## Features

- Convert tweet links into beautiful PNG/SVG/HTML screenshots
- Support multiple aspect ratios (1:1, 4:5, 16:9, etc.) for different social platforms
- Toggle between light and dark themes
- Customize background, hide stats, and more styling options

## Usage

Simply paste a tweet URL or ID in Cursor chat, and the Agent will automatically invoke this Skill to generate a screenshot:

```
twittershots https://twitter.com/username/status/1617979122625712128
```

### Examples

You can also specify format, theme, or aspect ratio:

```
Screenshot this tweet in dark mode: https://x.com/user/status/1617979122625712128
```

```
Generate a 4:5 ratio PNG of tweet 1617979122625712128 for Instagram
```

## Project Structure

```
.
├── SKILL.md                    # Skill definition and API documentation
├── scripts/
│   └── screenshot_tweet.py     # Command-line tool
└── README.md                   # About this skill
```

## Get API Key

Get your API key from the [TwitterShots Account Settings](https://twittershots.com/settings/keys) page.

---

Built for AI Agent · Powered by [TwitterShots](https://twittershots.com)
