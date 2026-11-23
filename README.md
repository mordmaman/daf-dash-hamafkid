# Daf Dash: HaMafkid

Revision games for **Bava Metzia, Perek HaMafkid (33b–36b)**. Play it at
https://mordmaman.github.io/daf-dash-hamafkid/

**Words:** Word Rain · Speed Round · Flashcards · Memory Pairs · Build the Line
**The sugya:** Who Pays? · Who Said It? · Chatat or Asham? · Cow Ping-Pong · The Bechina

Pick which dapim to revise, key Gemara words or sugya words, and which
direction to be asked in. Progress is saved on your own device only.

## Adding more

Everything is in `index.html`. The first `<script>` block is the content:
`DAFS`, `WORDS`, `LINES`, `CASES`, `SAID`, `KORBAN`. Add items tagged with the
next daf, add that daf to `DAFS`, and bump `VERSION` in `sw.js`.

The Aramaic text follows the William Davidson (Koren–Steinsaltz) vocalised
edition via Sefaria. Translations are simplified for learners; if you spot a
mistake, please open an issue.
