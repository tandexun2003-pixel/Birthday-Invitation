# Our Story · Lv. 6 (Birthday Edition)

A MapleStory-style birthday quest for Graz, from Dx (7 November). Open `index.html` in any browser to play.

## Before you send it — edit CONFIG
Open `index.html` in VS Code and find `const CONFIG` near the top of the `<script>`:

- `herName` – her name or nickname (shown in the HUD and the birthday line)
- `hisName` – your name on your dialogue tag
- `dateLabel` – e.g. "Saturday, 24 October"
- `firstBirthdayYear` – year of your 1st birthday together (montage shows #1–#5 from this year)
- `whatsappNumber` – your number, e.g. "6591234567", so her "WhatsApp him" button opens your chat
- `plan` – the schedule; the row titled `DINNER` is replaced by her pick

## Optional: real restaurant photos in the trailers
In `RESTAURANTS`, add image paths to `photos`, e.g. `photos: ["assets/blossom-1.jpg", "assets/blossom-2.jpg"]`.
They replace the pixel-art scenes with a slow zoom. Leave empty to keep the pixel art.

## Music
Every scene has its own 8-bit track (title, campus, boss battle, graduation, spot-the-difference,
birthday montage, an 8-bit "Happy Birthday", restaurant picker, final quest log). A small "♪ track name"
tag shows when it changes. To use a real song for any scene, drop the mp3 in `assets/` and set e.g.
`songs: { birthday: "assets/our-song.mp3" }` in CONFIG. Scene names: title, campus, battle, hall,
puzzle, night, birthday, lounge, romance.

On iPhone the game asks for "playback" audio, so it plays even with the silent switch on (like a video).
Media volume still needs to be up.

## Jump to a chapter (for testing)
Add `#ch2`, `#ch3` or `#pick` to the end of the URL.

## Story
1. Singapore Polytechnic – meet, Professor Snail, Calculus Slime boss fight (4 derivative questions)
2. SP Graduation 2023 – photo memory, Magic Mirror spot-the-difference (6 differences)
3. Birthdays #1–#5 montage
4. Today – 6th birthday, Lv. 6, restaurant trailers, her pick, final quest log

Ratings are a Google Maps snapshot from October 2026.
