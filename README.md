# X-ray any Instagram account

Thanks for commenting **x-ray**! This is the exact setup from the reel.

## What it does
You give Claude a handle. Claude Code opens that account in your own Chrome, collects their last 30 reels with views (pinned ones included), opens the best and worst performers, and works out what the hits do that the flops don't. Then it writes five reels on that pattern for your niche.

In the reel, it ran on an AI creator with about 91k followers. His hits claimed a result with real stakes (money, jobs, privacy) and showed the finished result on the cover. His flops were niche tasks with a dark or text-heavy first frame. It took Claude about 9 minutes.

## What you need
- Claude Code: https://claude.com/claude-code
- Google Chrome, logged in to Instagram
- The Claude in Chrome extension, connected to Claude Code (start Claude Code with `claude --chrome`)

## Run it
1. Make an empty folder and put `CLAUDE.md` in it.
2. In that folder, run `claude --chrome`.
3. Paste `prompt.txt` with the handle and your niche filled in.
4. Leave Chrome alone while it works, then read `xray.md`.

## Good to know
- It only reads public reels. It never likes, follows or messages anyone.
- Go slowly. If Instagram shows a "try again later" message, wait a few hours.
- Views alone aren't the whole story. Check the reasoning in `xray.md` before you copy a pattern.
