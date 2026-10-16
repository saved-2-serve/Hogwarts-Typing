# Hogwarts Typing Academy

A wizarding-school typing game that teaches touch typing step by step, in a single HTML file.

## ▶ [Play it in your browser](https://saved-2-serve.github.io/Hogwarts-Typing/)

No download needed. Just open the link and click anywhere to begin.

## Playing offline

1. Get the game file:
   - **Download just the game:** open [`Hogwarts Typing Academy.html`](Hogwarts%20Typing%20Academy.html) on GitHub, then click the **Download raw file** button (↓) at the top right of the file view.
   - **Or download everything:** click the green **Code** button on the repository page and choose **Download ZIP**, then unzip it.
2. Double-click **`Hogwarts Typing Academy.html`**. It opens in your web browser; nothing to install and no server needed.
3. Click anywhere on the title screen to begin.
4. Tell the Sorting Hat your name, then choose a house or let the Hat decide.

You need a physical keyboard. The game isn't designed for phones or tablets.

Fonts load from Google Fonts when you're online. Offline, the game still works and uses your system's serif and monospace fonts instead.

## Game modes

Pick a mode from the Great Hall by clicking it or pressing its number key.

### 1 · Classes
17 lessons, from your First Year to the N.E.W.T.s. Each one introduces a few new keys:

| Year | Classes | Keys |
|------|---------|------|
| First | Charms, Transfiguration, Herbology | F J, D K, S L (home row) |
| Second | Potions, Flying Lessons | A ;, G H |
| Third | Astronomy, Care of Magical Creatures | E I, R U |
| Fourth | History of Magic, Divination | T O, Q W Y P |
| Fifth | Ancient Runes, Arithmancy, Defence Against the Dark Arts | N M, C V B, X Z , . |
| Sixth | Advanced Charms, Gringotts Accounting | Shift / capitals, numbers |
| Seventh | Spellwork, O.W.L. Exam, N.E.W.T. Finals | Spell names, full sentences, long passages |

How a lesson works:

- An intro card shows each new key and the finger that presses it.
- Each lesson has four rounds of typing (three for the N.E.W.T. Finals).
- The on-screen keyboard lights up the next key, and the hand diagram shows which finger to use.
- The text only moves forward when you press the correct key, which trains accuracy.
- At the end you're graded like a wizarding exam, with stars:

| Grade | Stars | Accuracy |
|-------|-------|----------|
| Outstanding | ★★★ | 97% or more |
| Exceeds Expectations | ★★ | 90% or more |
| Acceptable | ★ | 75% or more |
| Poor | none | below 75% |

You need at least one star to unlock the next class.

### 2 · Dementor Defence
Dementors drift towards the castle, each carrying a word. Type the word to strike that dementor with a charm.

- **Backspace** releases your current target.
- Every dementor you banish fills the **Patronus** meter. When it's full, press **Enter** to clear the whole screen.
- If 5 dementors reach the castle, the duel is over.
- There are three difficulties: First Year, Fifth Year and Seventh Year (real incantations).

### 3 · Snitch Chase
A broom race on the Quidditch pitch. Each correct letter pushes your broom forward. Reach the hoops before the rival Seeker to catch the Golden Snitch. There are five rivals, from 12 to 55 words per minute.

### 4 · Room of Requirement
Adaptive practice. The game keeps track of every key you miss. Once it has enough data, this mode shows a red-to-green heat map of your keyboard and builds drills around your five weakest keys.

## Controls

| Key | Action |
|-----|--------|
| Space / Enter | Begin a lesson or continue |
| Esc | Go back / leave the current activity |
| R | Retry a lesson from the results screen |
| 1–4 | Choose a mode in the Great Hall |

The buttons at the top right of the screen toggle **sound effects** and **music** and open **Settings**.

## House points
Everything you do earns points for your house: finishing classes, banishing dementors, surviving waves and catching Snitches. Your total is shown at the top of the screen.

## Settings (⚙)
- **Unlock all classes:** skip ahead if you can already type.
- **Visit the Sorting Hat again:** change your name or house.
- **Reset all progress:** start over from scratch.

## Saving
Progress saves automatically in your browser's local storage. Keep these in mind:

- Progress belongs to the browser you play in. Opening the file in a different browser starts fresh.
- Clearing your browser data erases your progress.
- Private/incognito windows don't keep progress after you close them.

## Under the hood
- One self-contained HTML file using plain HTML, CSS and JavaScript, with no libraries.
- All graphics are drawn live on canvas: the castle, lake, candles, dementors, brooms and Snitch.
- All sound and music is generated in the browser with the Web Audio API, so there are no audio files.

## License
The code is released under the [MIT License](LICENSE).

---

*A fan-made learning game. Harry Potter and related names belong to their respective owners. This project is not affiliated with or endorsed by them.*
