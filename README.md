# Fashion Trend Forecasting

A Codex skill for designers and fashion brands: research future consumer needs, develop seasonal trend stories, and translate them into colour palettes, fabrics, silhouettes, prints, garments and visual moodboards.

Full forecasts include a moodboard for every story and season. Three stories across S/S and A/W produce six boards. Explicit text-only requests and narrower questions retain their requested scope.

## Install in Codex

Paste this into Codex:

```text
Use $skill-installer to install
https://github.com/hansi-collab/fashion-trend-forecasting/tree/main/skills/fashion-trend-forecasting
into my user-level ~/.agents/skills directory. Preserve any existing
installation before replacing it and verify the installed reference links.
```

The complete skill is in [skills/fashion-trend-forecasting](skills/fashion-trend-forecasting). For a private repository, each teammate needs repository read access and an authenticated GitHub account.

For manual installation, download the repository, then copy the entire `skills/fashion-trend-forecasting` folder into:

- macOS/Linux: `~/.agents/skills/`
- Windows: `%USERPROFILE%\.agents\skills\`

The installed entry point must be `fashion-trend-forecasting/SKILL.md`, with the adjacent `agents` and `references` folders preserved. Codex detects skill changes automatically; restart Codex if it does not appear.

[Official OpenAI skill documentation](https://learn.chatgpt.com/docs/build-skills).

## Run

```text
Use $fashion-trend-forecasting to create a full upcoming-year womenswear
forecast for the global market, covering S/S and A/W. Include three trend
stories, colour palettes, fabrics, silhouettes, prints, key garments,
design details, dated sources and a visual moodboard for every story
and season.
```

Specify another market, category, season or price level when needed. The default is international womenswear for fashion designers and brand owners.

## What the skill produces

- A dated brief, consumer drivers, prioritised opportunities and original seasonal stories.
- Colour palettes with names, screen HEX references, roles, pairings and garment applications.
- Fabrics, surfaces, proportions, key garments, prints, trims and styling direction.
- Original landscape moodboards, each with the seasonal palette, four fabric close-ups, two print/pattern examples and three garment examples.
- Sampling priorities, tech-pack implications, evidence limits and next validation steps.
- Inline moodboards plus saved images and generation prompts; a downloadable ZIP for multi-board sets.

## Capabilities and limits

Current research requires web browsing. Complete visual forecasts also require image generation, image inspection and file creation/download support in the host Codex environment. Installing these instructions does not enable tools that the host does not provide. Missing evidence or unavailable image generation must be reported; a prompt list alone does not complete the moodboard deliverable.

The skill specifies no required API key, third-party executable, private dataset or WGSN subscription.

This is independent research informed by WGSN's publicly documented approach. It is not affiliated with WGSN or Coloro, does not reproduce their subscription reports, and does not claim equivalent predictive accuracy. Generated images are design concepts. Screen colours and material proposals require physical references, supplier confirmation and sample approval before production.

## Repository contents

```text
skills/fashion-trend-forecasting/
  SKILL.md
  agents/openai.yaml
  references/method-and-sources.md
  references/report-contract.md
```

Installed copies are snapshots. Update and review the skill deliberately when the repository changes.
