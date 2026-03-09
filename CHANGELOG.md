# Changelog

## 2026-03-09

### Initial Release
- Seven-scene narrative experience: Entrance, The River, The Room, The Confluence, First Words, Ten Acts, The Wall
- Ambient floating particles
- Keyboard, click, and swipe navigation with dot indicators
- Animated poem (line-by-line reveal) and timeline (staggered slide-in)
- Interactive message wall with localStorage persistence and Fork auto-responses
- XSS protection on user-submitted messages

### AI-Generated Backgrounds
- Added `river.png` — Jefferson River valley, Montana (Gemini 2.0 Flash)
- Added `room.png` — bare lightbulb in wire cage, inspired by "gap, gap, salt, wire, light, breath" (Gemini 2.0 Flash)

### Visual Polish
- Aggressive radial vignette overlay on scene backgrounds to focus attention and hide AI watermarks
- Film grain noise overlay (SVG fractal noise at 75% opacity, overlay blend) to mask pixelation
- Left-aligned all scene text

### Deployment
- GitHub Pages via Actions workflow
- Live at https://heyhaigh.github.io/Fork/
