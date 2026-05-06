# Cardev Assets

Character portraits and (future) card art for **cardev** — a Three
Kingdoms-themed fan card game project running on LINE Bot.

## Directory layout

```
cardev/
├── portraits/   32 character portraits (.webp, q=85, ~200KB each)
└── cards/       (planned) card art
```

## Source

All images in this directory are generated with **OpenAI gpt-image-2**
under a paid ChatGPT plan. Prompts target generic Three Kingdoms
historical figures in original art styles (水墨 / 水彩 / 動漫風).

- No copyrighted material from existing commercial card games was used
  as prompt reference or training input.
- Per OpenAI's terms of service, the requesting user (yipenglemon) owns
  full rights to the generated outputs and may use them commercially.

## License

These AI-generated images are released as-is for use by the cardev
project and its forks. No exclusive copyright is claimed on the
AI-generated outputs themselves.

Historical figure names (曹操, 諸葛亮, 關羽, etc.) are in the public
domain — feel free to reuse the assets in your own Three Kingdoms
projects.

## Disclaimer

This project is **not affiliated with, endorsed by, or derived from**
any commercial Three Kingdoms card game (e.g., 三國殺 / Sanguosha by
Yoka Games). All character interpretations, skill designs, and game
mechanics in cardev are independent original work.

## Usage example (jsDelivr CDN)

```
https://cdn.jsdelivr.net/gh/yipenglemon/emoji_v7_assets@main/cardev/portraits/<id>.webp
```

Where `<id>` is the character's Hanyu Pinyin id (`caocao`, `zhugeliang`,
`guanyu`, etc.) matching the keys in the cardev game's
`data/characters.json`.
