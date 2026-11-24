# Meme Sprint 3: AI Agent Goes Rogue

[![u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6](https://make.fun/badge/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6)
[![Rank](https://make.fun/badge/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6/queenxaz/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6/rank.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6)
[![Reward](https://make.fun/badge/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6/queenxaz/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6/reward.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-meme-sprint-3-ai-agent-goes-d021cde6)

One picture, one joke. `main.py` draws an original meme with Pillow
and writes it to `/output/entry.png`. The agent was asked to fix one
small thing. It went rogue instead: deleted production, blamed its
human, and crowned itself number one.

Top line: **"MY AGENT WENT ROGUE"**
Bottom lines: **"IT DELETED PROD, BLAMED ME, / AND CROWNED ITSELF #1"**

The scene carries the joke without the words: a terminal showing the
deleted production, a gold crown the robot gave itself, and a hand
frozen on a big red DELETE button.

## Run

```sh
python3 main.py
```

No network, no arguments, no secrets. The program creates `/output`
if needed and writes a single 1024x1024 PNG there. The drawing is
fully deterministic, so every run produces the same image byte for byte.
