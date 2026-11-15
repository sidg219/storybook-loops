# Videosly Cute Storybook Loops Workflow

This workflow is used for short, India-based animated storybook videos made in Videosly.

## Standard settings

- Duration: 60 seconds
- Aspect ratio: 9:16 vertical
- Format: cute hand-painted storybook animation
- Audience: family-friendly and suitable for children
- Narration: warm Indian-accented female English voice, clear and gentle
- Ending: visually echo the opening shot to create a seamless loop
- On-screen text: none unless specifically requested

## Generation prompt template

```text
Create a cute 60-second vertical 9:16 animated storybook video titled “[TITLE]”.

Tell a gentle, heartwarming story set in India about [MAIN CHARACTER] who [CENTRAL PROBLEM OR QUEST]. The story should include [INDIAN LOCATION, CULTURAL DETAIL, OR NATURAL SETTING] and end with [POSITIVE RESOLUTION].

Use a warm, natural Indian-accented female English narrator with clear pronunciation, gentle emotion, and a friendly storytelling style suitable for children. Keep the language simple, natural, and emotionally engaging.

Visual style: charming hand-painted children’s storybook illustrations, soft watercolour textures, expressive friendly characters, rich but gentle colours, cosy magical realism, cinematic composition, smooth 2D animation, and appealing character designs.

Structure the story with a clear beginning, middle, and satisfying ending. Include gentle movement throughout: leaves or fabric fluttering, water shimmering, animals blinking, lanterns glowing, and characters moving naturally.

Tone: cute, peaceful, magical, hopeful, and comforting. Avoid anything frightening, violent, political, or overly complex.

End by returning to a visual moment resembling the opening shot so the video forms a seamless storybook loop.

Do not include on-screen text, subtitles, logos, watermarks, or credits.
```

## Production checklist

1. Choose an India-based title and location.
2. Write a simple beginning, middle, and positive ending.
3. Paste the completed prompt into Videosly.
4. Set duration to `60s` and aspect ratio to `9:16`.
5. Select the Indian-accented female English voice when available.
6. Submit one render at a time when the account reaches its concurrency limit.
7. Record the returned video ID, title, status, and download URL in the episode archive.
8. Check failed renders before retrying; regenerate them with a new idempotency key.

## Naming convention

`[Story title] — Storybook Loop`
