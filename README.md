# Paper

![The Paper look on an agent chat: prompts, tool rows, a reply and a code block](screenshots/chat.png)

A warm, roomy reading look for agent chats in cmux: serif replies on off-white paper, ink-brown text,
a sepia accent, and soft rounded prompts.

Paper picks a light paper theme with a sepia accent, but its chat stylesheet is made only from the
theme's own colors, so `agent-pane/theme.css` on its own reads over a dark theme as well as a light
one (WCAG AA, checked in both).

It is built only from public surfaces, so you can copy any part of it:

| File | What it does |
| --- | --- |
| `cmux-setup.json` | Picks the theme file; sets the chat's serif font, size, line height and width and the sidebar's density |
| `themes/paper.json` | The colors, surfaces and density |
| `agent-pane/theme.css` | The prompt bubble and cards, with `cmux.agentPane.style/1` tokens only |
| `customize/` | A reading hover card with the task in full, and calm sidebar rows |

```sh
cmux setup install github.com/manaflow-ai/cmux-paper-look
cmux setup remove manaflow-ai/paper-look
```

While it is installed, its `customize/` view stands in for your own sidebar view, if you have one;
`cmux setup remove` puts yours back.

How looks like this one are written: [look-addons.md](https://github.com/manaflow-ai/cmux/blob/639a429492936ae3b4f0d4a1e6d7fbf66e708520/docs/cmux-next/look-addons.md).
